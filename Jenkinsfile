pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'ansible-playbook site.yml'
      }
    }
  }
}