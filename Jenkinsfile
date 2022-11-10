pipeline {
    agent any

    stages {
        stage('Build'){
            steps {
                sh 'echo "stage build"'
            }
        }
        stage('Test'){
            steps {
                sh 'echo "stage test"'
                junit 'reports/**/*.xml'
            }
        }
        stage ('Deploy'){
            steps {
                sh 'echo "stage deploy"'
            }
        }
    }


}