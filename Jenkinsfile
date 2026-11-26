pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/kikysena13/CICD.git'
            }
        }
        stage('Build') {
            steps {
                // Ganti perintah di bawah sesuai stack project Anda
                sh 'ls -la'
            }
        }
    }
}
