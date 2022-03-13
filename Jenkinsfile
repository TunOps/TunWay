pipeline {
  environment {
    registry = 'labdus/jenkins'
    registryCredential = 'docker'
    dockerImage = ''
  }
agent any
stages {
  stage('Git') {
      steps {
        echo 'Cloning'
        git branch: 'master', url: 'https://github.com/TunOps/TunWay.git'
      }
  }
}
}
}
