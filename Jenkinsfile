node {
  checkout scm

  docker.image('node:16-buster-slim').withRun('-p 3000:3000') { ->
    stage('build') {
      sh 'npm install'
    }

    stage('test') {
      sh 'npm test'
    }
  }
}