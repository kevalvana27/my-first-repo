pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
               git 'https://github.com/kevalvana27/my-first-repo.git'
            }
        }
        
        stage('Build') {
            steps {
               bat 'javac Demo.java'
            }
        }
          
        stage('Execute') {
            steps {
               bat 'java Demo'
            }
        }
        
    }
}
