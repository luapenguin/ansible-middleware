pipeline {
  agent {
    node {
      label 'node04'
    }

  }
  stages {
    stage('') {
      steps {
        ansiblePlaybook(playbook: 'main.yaml', inventory: 'Linux/inventory')
      }
    }

  }
}