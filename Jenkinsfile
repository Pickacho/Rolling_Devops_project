pipeline {
  agent any
  stages {
    stage('githubpull') {
      steps {
        git(url: 'https://github.com/Pickacho/Rolling_Devops_project.git', branch: 'Dev', poll: true, credentialsId: '1')
        sh '''whoami
ls'''
      }
    }

  }
}