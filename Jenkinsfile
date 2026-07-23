pipeline {

    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Checking files'
            }
        }

        stage('List Files') {
            steps {
                bat 'dir'
            }
        }

        stage('Read HTML') {
            steps {
                bat 'type index.html'
            }
        }

    }

}