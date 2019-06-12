pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat label: '', script: 'mvn clean install'
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
