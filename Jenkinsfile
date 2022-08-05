pipeline {
    agent any

    stages 
    {
        stage('Start') {
            steps {
                echo 'Hello world'
            }
        }

        stage ('Invoke_pipeline') {
            steps {
                sh 'ls'
            }
        }

        stage('End') {
            steps {
                sh 'ls'
            }
        }
    }
}
