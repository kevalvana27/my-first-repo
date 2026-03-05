pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
               git 'https://github.com/kevalvana27/my-first-repo.git'
            }
        }
        
        stage('check1') {
            steps {
               bat 'javac Demo.java'
            }
        }
          
        stage('check2') {
            steps {
               bat 'java Demo'
            }
        }
        
    }
}
