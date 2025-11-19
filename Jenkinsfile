node{
  stage('Build'){
        echo 'started building...'
        sh 'mvn clean install'
    }
  stage('Test'){
    echo 'started testing...'
    sh 'mvn test'
  }
  stage('Deploy'){
    echo 'started Deploying...'
    sh 'echo deployment completed'
  }
  
}
