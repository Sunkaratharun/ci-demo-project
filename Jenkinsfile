pipeline {
    agent any

    stages {

        

        stage('Build') {
            steps {
                bat 'type calculator.py'
            }
        }

        stage('Run Script') {
            steps {
                bat 'python my calculator.py'
            }
        }

    }
}
