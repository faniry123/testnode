pipeline {
  agent any
  tools {nodejs "Node"}

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
