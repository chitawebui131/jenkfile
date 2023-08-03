pipeline {
    agent any

    stages {
        stage('Apt update') {
            steps {
                // Install Maven on Ubuntu
                sh 'sudo apt-get update -y'
                     }
        }
        stage('Install Maven') {
            steps {
         
                sh 'sudo apt-get install -y maven'
            }
        }
        stage(' Maven Version') {
            steps {
            // Display Maven version
                sh 'mvn --version'
            }
        }
    }
}
