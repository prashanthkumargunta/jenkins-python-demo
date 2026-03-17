pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                echo 'Cloning from GitHub...'
            }
        }

        stage('Run Python') {
            steps {
                sh 'python3 app.py'
            }
        }
    }
}