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
        stage('Python Execution') {
            steps {
                echo 'Temporary Buffer Loaded'
                build 'PyPRJ'
            }
        }
        stage('Experiment on Code'){
            steps{
                build 'TestPRJ'
            }
        }
    }
}
