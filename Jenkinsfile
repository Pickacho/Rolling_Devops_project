pipeline {
  agent any
  stages {
    stage('githubpull') {
      steps {
        git(url: 'https://github.com/Pickacho/Rolling_Devops_project.git', branch: 'dev', poll: true)
        sh '''whoami
ls'''
      }
    }

  }
}