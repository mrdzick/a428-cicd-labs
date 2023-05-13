node {
  stage('Checkout') {
    checkout scm
  }

  stage('Build and Test') {
    sh 'npm install'
    sh 'npm test'
  }
}