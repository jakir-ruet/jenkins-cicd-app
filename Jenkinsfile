# npm version checking

pipelines {
    agent any

    stages {
        stage('Check Node.js Version') {
            steps {
                sh 'node -v'
                sh 'npm -v'
            }
        }
    }
}
