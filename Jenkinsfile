pipeline {
    agent any

    stages {
        stage('Specifying Pipeline') {
            steps {
                echo 'SCM Loaded'
            }
        }
        stage('Test') {
            steps {
                echo 'Running Interpretor'
            }
        }
        stage('GIT-JENKINSFILE') {
            steps {
                echo 'Temporary Buffer Loaded'
            }
        }        
        stage('Execute Python File'){
            steps{
                build 'TestPRJ'
            }
        }
    }
}
