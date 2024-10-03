pipeline {
    agent any

    stages {
        stage('STARTING') {
            steps {
                echo "I'm starting a pipeline CICD"
            }
        }
        stage('BUILD') {
            steps {
                echo 'Developpement build'
            }
        }
        stage('TEST') {
            steps {
                echo 'Testing code'
            }
        }
        stage('DEPLOY') {
            steps {
                echo 'Deployment'
            }
        }
    }
}
