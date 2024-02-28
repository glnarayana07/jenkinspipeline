pipeline {
  agent any
  stages {
    stage('development') {
      steps {
        echo 'this is the devolepment'
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'this is the testing stage'
          }
        }

        stage('build') {
          steps {
            echo 'this is the build stage'
          }
        }

        stage('deploye') {
          steps {
            echo 'this the deployement'
          }
        }

        stage('operation') {
          steps {
            echo 'this is the operation'
          }
        }

      }
    }

  }
}