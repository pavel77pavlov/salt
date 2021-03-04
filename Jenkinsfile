pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh 'salt \\* test.ping'
      }
    }
  }
}
