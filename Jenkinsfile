@Library('your-shared-library-name') _


pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout(stageParams: [
                    branch: 'main',
                    url: 'https://github.com/example/repository.git'
                ])
            }
        }
        // Add more stages as needed
    }
}

