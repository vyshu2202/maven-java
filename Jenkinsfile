pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
// node {
//     properties([
//         pipelineTriggers([
//             [$class: 'GitHubPushTrigger']
//         ])
//     ])

//     stage('Build') {
//         bat 'mvn clean install'
//     }

//     stage('Test') {
//         bat 'mvn test'
//     }

//     stage('Deploy') {
//         bat 'echo Deployment Completed'
//     }
// }
