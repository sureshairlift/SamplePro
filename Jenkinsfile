pipeline {
    agent any
    stages {
        stage('go version') {
            steps {
                sh 'go version'
                 sh 'echo "succes verion"'
            }
        }
        stage('RUN') {
            steps {
                sh 'go run main.go'
                 sh 'echo "succes verion"'
            }
        }

        stage('build') {
            steps {
                sh 'go build main.go'
            }
        }
    }
}
