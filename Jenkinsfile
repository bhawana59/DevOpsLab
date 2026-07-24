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
        sh 'ls -la'
    }
}

stage('Read HTML') {
    steps {
        sh 'cat index.html'
    }
}

    }

}