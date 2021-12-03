pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Built' 
            }
        }
         stage('Test') {
            steps {
                echo 'Tested' 
            }
        }
         stage('Deploy') {
            steps {
                echo 'deployed' 
            }
        }
    }
        post{
            always{
                echo 'Success or failure'
            }
             success{
                echo 'Success '
            }
             failure{
                echo 'Failure'
            }
        }
    
}
