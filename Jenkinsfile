pipeline {
  agent any
  stages {
    stage('Poll') {
      steps {
        git(url: 'https://github.com/murthychandrappa/cicdrepo.git', branch: 'master', poll: true)
      }
    }
  }
}