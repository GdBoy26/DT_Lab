pipeline {
    agent {
        label 'slave1'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building Calculator Project...'
                sh 'echo "Source code retrieved successfully."'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Calculator Project...'
                sh 'test -f readme.txt'
            }
        }

        stage('Result') {
            steps {
                echo 'Build and Test Completed Successfully.'
            }
        }
    }
}
