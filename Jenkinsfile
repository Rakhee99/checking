pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
               bat 'python add.py'
            }
        }
      stage('Testing Stage'){
        steps{
          echo 'Test is completed'
        }
      }
      stage ('Deployment Stage'){
        steps{
          echo 'Deployment successful'
        }
      }
    }
}
