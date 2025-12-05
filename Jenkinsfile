// npm version checking

pipeline {
    agent any

    stages {
        stage('Check Version') {
            steps {
                sh '''
                npm --version
                '''
            }
        }
    }
}
