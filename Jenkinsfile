pipeline {
    agent any
    environment {
        python="C:\\Python313\\python.exe"
    }
    stages {
        stage('Build') {
            steps {
                bat "python3 code.py"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
