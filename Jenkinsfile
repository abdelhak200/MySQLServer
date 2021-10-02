pipeline {
  agent {
    dockerfile {
      filename 'C:/windows/system32/config/systemprofile/AppData/Local/Jenkins/.jenkins/workspace/MySQLServer1_master/docker-compose.yml'
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