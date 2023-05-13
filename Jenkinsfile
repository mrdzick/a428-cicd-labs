node {
  stage('Checkout') {
    checkout scm
  }

  stage('Install Node') {
    sh 'apt-get update'
    sh 'apt-get install -y nodejs'
  }

  stage('Build and Test') {
    sh 'npm install'
    sh 'npm test'
  }
}