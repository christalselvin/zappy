pipeline {
    agent any

    stages {

        stage('Test Stage') {
            steps {
                echo 'Jenkins pipeline is working!'
            }
        }

        stage('Run Linux Command') {
            steps {
                sh 'echo Hello DevOps'
                sh 'date'
                sh 'hostname'
            }
        }

    }
}
