pipeline {
  agent any
  stages {
    stage('githubpull') {
      parallel {
        stage('githubpull_dev') {
          steps {
            git(url: 'https://github.com/Pickacho/Rolling_Devops_project.git', branch: 'Dev', poll: true, credentialsId: '1')
            sh '''whoami
ls'''
          }
        }

        stage('githubpull_staging') {
          steps {
            git(url: 'https://github.com/Pickacho/Rolling_Devops_project.git', branch: 'staging', credentialsId: '1', poll: true)
          }
        }

      }
    }

  }
}