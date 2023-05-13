node {
  stage('Checkout') {
    checkout scm
  }

  stage('Install Node') {
    sh 'sudo apt-get update'
    sh 'sudo apt-get install -y nodejs'
  }

  stage('Build and Test') {
    sh 'npm install'
    sh 'npm test'
  }
}