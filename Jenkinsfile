pipeline {
  agent any
  stages {
    stage('Test (echo \'Testing..\')') {
      parallel {
        stage('Test (echo \'Testing..\')') {
          steps {
            echo 'echo \'Testing..'
          }
        }

        stage('Deploy') {
          steps {
            echo 'echo \'Deploying....\''
          }
        }

      }
    }

  }
}