pipeline {
  agent any
  Stages {
  Stage('Build') {
    steps {
      echo 'Build step'
      sleep 10
    }
  }
  stage('Test') {
    steps {
      echo 'Test step'
    }
  }
   Stage('deploy') {
    steps {
      echo 'deploy step'
      sleep 10
    }
  }
  stage('Docker') {
    steps {
      echo 'Image step'
    }
  }
}
}
