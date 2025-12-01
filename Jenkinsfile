node {

    stage('Checkout') {
        echo 'Checking out code...'
        checkout scm
    }

    stage('Build') {
        echo 'Started building...'
        bat 'mvn clean install'
    }

    stage('Test') {
        echo 'Started testing...'
        bat 'mvn test'
    }

    stage('Deploy') {
        echo 'Started Deploying...'
        bat 'mvn deploy'
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
