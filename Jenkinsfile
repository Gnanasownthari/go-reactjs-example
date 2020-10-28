pipeline {
  agent none
  stages {
    stage('Install') {
      steps {
        echo 'Installed'
      }
    }

    stage('Build') {
      steps {
        echo 'Build sucessfully'
      }
    }

    stage('Report') {
      steps {
        junit(healthScaleFactor: 2, testResults: 'none')
      }
    }

  }
}