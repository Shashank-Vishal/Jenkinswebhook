pipeline {
    agent any

    // tools {
    //     nodejs "nodejs" // This assumes you have a Node.js installation named 'nodejs' configured in Jenkins
    // }

    // environment {
    //     // Define environment variables here
    // }

    stages {
        stage('Checkout') {
            steps {
              git branch: 'main', url: 'https://github.com/Shashank-Vishal/Jenkinswebhook.git'
                }
        }
        
        // stage('Install Dependencies') {
        //     steps {
        //         script {
        //             // Install npm dependencies
        //             sh 'npm install'
        //         }
        //     }
        // }

        // stage('Run Tests') {
        //     steps {
        //         script {
        //             // Run tests
        //             sh 'npm test'
        //         }
        //     }
        // }

        // stage('Build') {
        //     steps {
        //         script {
        //             // Build the project
        //             sh 'npm run build'
        //         }
        //     }
        // }

        // stage('Deploy') {
        //     when {
        //         branch 'main' // Only deploy from the main branch
        //     }
        //     steps {
        //         script {
        //             // Deployment logic here
        //             // For example, copying build artifacts to a server
        //             sh '''
        //             # Example deployment script
        //             scp -r ./build user@yourserver:/path/to/deploy
        //             '''
        //         }
        //     }
        }
    }

//     post {
//         always {
//             // Archive build artifacts or run cleanup steps
//             archiveArtifacts artifacts: 'build/**/*', allowEmptyArchive: true
//         }
//         success {
//             // Notify on success
//             echo 'Build succeeded!'
//         }
//         failure {
//             // Notify on failure
//             echo 'Build failed!'
//         }
//     }
// }

