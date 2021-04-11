pipeline {
    agent { 
        dockerfile {
        filename 'Dockerfile',
        label 'docker'
        }
         
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}

