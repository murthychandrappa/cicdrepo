pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        git(poll: true, url: 'https://github.com/murthychandrappa/cicdrepo.git', branch: 'master')
      }
    }
  }
}