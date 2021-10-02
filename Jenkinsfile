pipeline {
  agent {
    dockerfile {
      filename 'docker-compose'
    }

  }
  stages {
    stage('') {
      steps {
        sh 'docker-compose up -d'
      }
    }

  }
}