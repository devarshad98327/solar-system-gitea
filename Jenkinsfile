pipeline {
    agent any
    tools{
        nodejs 'nodejs-24.2.0'
    }
    stages {
        stage('Check Node and npm Version') {
            steps {
                bat 'node -v'      // Prints Node.js version
                bat 'npm -v'       // Prints npm versio
            }
        }
    }
}
