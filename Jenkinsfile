pipeline {
    agent any

    stages {
        stage('code pull') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('Docker image build') {
            steps {
                echo 'Build docker image'
            }
        }
        
        stage('docker image push') {
            steps {
                echo 'push docker image'
            }
        }
        
        stage('deploy on UAT env') {
            steps {
                echo 'deployed on UAT env'
            }
        }
        
        stage('deploy on PROD env') {
            steps {
                echo 'Deployed on PROD env'
            }
        }
    }
}
