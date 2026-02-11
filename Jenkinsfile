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
                bat 'AppData\\Local\\Microsoft\\WindowsApps\\python.exe'
            }
        }

    }
}
