pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
               git 'https://github.com/kevalvana27/my-first-repo.git'
            }
        }
        
        stage('Publish') {
            steps {
                publishHTML ([
                    allowMissing:true,
                    alwaysLinkToLastBuild:false,
                    keepAll:false,
                    reportDir:'.',
                    reportFiles:'jenhtml1.html',
                    reportName:'My html Publish'
                ])
            }
        }
    }
}
