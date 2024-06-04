pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {

                 checkout scm
            }
        }

        stage('Build') {
            steps {

                sh 'javac Demo.java'
            }
        }
  stage('Run') {
            steps {
                // Run the compiled Java program
                sh 'java Demo'
            }
        }
    }
}

