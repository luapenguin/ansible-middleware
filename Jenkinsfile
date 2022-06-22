pipeline {
  agent any
  stages {
    stage('') {
      steps {
        ansiblePlaybook(playbook: 'main.yaml', become: true, becomeUser: 'root')
      }
    }

  }
}