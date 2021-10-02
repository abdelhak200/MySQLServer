pipeline {
  agent {
    dockerfile {
      filename 'docker-compose'
    }

  }
  stages {
    stage('UP') {
      steps {
        sh 'docker-compose up -d'
      }
    }

  }
}
