pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build'
          }
        }

        stage('') {
          agent any
          steps {
            echo 'SideCar'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Test'
      }
    }

  }
}