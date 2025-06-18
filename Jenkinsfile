pipeline {
    agent any
    tools {
    nodejs 'NodeJS 24.2.0'
}
    stages {
        stage('Install dependencies') {
            steps {
                bat 'npm install --no-audit'
            }
        }
    }
}
