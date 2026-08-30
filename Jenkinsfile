pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }

        stage('Test') {
            steps {
                sh 'python3 test_calculator.py'
            }
        }
    }
}
