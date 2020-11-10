pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'apk add perl bash'
                sh 'perl -c program.pl'
            }
        }
        stage('Test') { 
            steps {
                sh 'bash test.sh'
            }
        }
    }
}
