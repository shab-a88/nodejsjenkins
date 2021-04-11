pipeline {
    agent 
    { 
        dockerfile true,
        label 'docker' 
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