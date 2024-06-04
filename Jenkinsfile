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

                sh 'javac Main.java'
            }
        }
  stage('Run') {
            steps {
                // Run the compiled Java program
                sh 'java Main'
            }
        }
    }
}

