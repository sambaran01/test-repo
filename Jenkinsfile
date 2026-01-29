pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/sambaran01/test-repo.git'
            }
        }

        stage('Run Python') {
            steps {
                bat 'python gg.py'
            }
        }
    }
}
