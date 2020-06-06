pipeline {
  agent any
  stages {
        stage('githubpull_staging') {
          steps {
            git(url: 'https://github.com/Pickacho/Rolling_Devops_project.git', branch: 'staging', credentialsId: '1', poll: true)
          }
        }

      }
    }

  }
}
