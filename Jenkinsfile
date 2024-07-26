pipeline {
    agent any

    stages {
        stage('Hello1') {
            steps {
                git branch: 'main', credentialsId: '1efce57b-4df9-4715-9c62-dac27109bb4a', url: 'https://github.com/shanthakumar1987/ntsrepo3.git'
            }
        }
        stage('Hello2') {
            steps {
                bat 'terraform init'
            }
        }
        stage('Hello3') {
            steps {
                echo 'Hello World 3'
            }
        }
    }
}
