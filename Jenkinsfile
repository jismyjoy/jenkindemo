pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                echo 'Cleaning..'
                sh 'mvn -B -DskipTests clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Integration tests') {
            steps {
                echo 'Run integration test....'
            }
        }
    }
}