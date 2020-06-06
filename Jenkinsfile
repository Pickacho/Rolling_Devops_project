pipeline {
  agent any
  stages {
        stage('Github_pull_prod') {
          steps {
            git(url: 'https://github.com/Pickacho/Rolling_Devops_project.git', branch: 'Prod', credentialsId: '12', poll: true)
          }
        }

      }
    }

  }
}
