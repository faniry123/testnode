pipeline {
  agent { label 'agentlinux' }

  stages {
    stage('Check Node and NPM versions') {
      steps {
        script {
          sh 'node --version'
          sh 'npm --version'
        }
      }
    }
    // Ajoutez d'autres étapes au besoin
  }
}
