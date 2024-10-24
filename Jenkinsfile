pipeline {
    agent any

    tools {
        // Use the NodeJS tool configured in Jenkins (e.g., 'nodejs_16')
        nodejs 'nodejs'
    }

    stages {
        stage('Install Dependencies') {
            steps {
                script {
                    // Run npm install
                    sh 'npm install'
                }
            }
        }

        // stage('Build') {
        //     steps {
        //         script {
        //             // Run build scripts
        //             sh 'npm run build'
        //         }
        //     }
        // }

        // stage('Test') {
        //     steps {
        //         script {
        //             // Run tests
        //             sh 'npm test'
        //         }
        //     }
        // }
    }
}
