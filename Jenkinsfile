pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Start Building'
            }
        }
        stage('Test') {
            steps {
                echo 'Test App'
            }
        }
        stage('Clean') {
            steps {
                echo 'Cleaning Workspace'
            }
        }
        stage('Build MAVEN JAR'){
            steps{
                build 'TestPRJ'
            }
        }
    }
}
