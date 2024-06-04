pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {

                git 'https://github.com/Vijayb8095/jenkinsmultibranch.git'
            }
        }

        stage('Build') {
            steps {

                sh 'mvn clean install'
            }
        }
    }
}

