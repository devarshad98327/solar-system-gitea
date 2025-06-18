pipeline {
    agent any
    tools {
    nodejs 'NodeJS 24.2.0'
}
    stages {
        stage('Install dependencies') {
            steps {
                bat 'node -v'      // Prints Node.js version
                bat 'npm -v'       // Prints npm versio
            }
        }
    }
}
