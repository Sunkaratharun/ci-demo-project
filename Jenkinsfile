pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                git 'https://github.com/Sunkaratharun/ci-demo-project.git'
            }
        }

        stage('Build') {
            steps {
                bat 'type calculator.py'
            }
        }

        stage('Run Script') {
            steps {
                bat 'python calculator.py'
            }
        }

    }
}
