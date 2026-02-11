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
                bat bat '"C:\\Users\\SWAPNA MANI\\AppData\\Local\\Programs\\Python\\Python314\\python.exe" calculator.py'

            }
        }

    }
}
