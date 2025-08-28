pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Hello Build stage"
                sh 'hostname'
            }
        }
        stage('Test') {
            steps {
                echo "Hello Test Stage"
                sh 'pwd'
            }
        }
        stage('Deploy') {
            steps {
                echo "Hello Deploy Stage"
                sh 'date'
            }
        }
    }
}
