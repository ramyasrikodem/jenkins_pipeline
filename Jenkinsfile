pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
            // Remove or comment out this block
            // post {
            //     always {
            //         mail to: 'ramyasrikodem@gmail.com',
            //              subject: 'Build Status Email',
            //              body: 'Build log attached'
            //     }
            // }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }

        }
    }
}