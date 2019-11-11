pipeline {
  agent any
  stages {
    stage('check out') {
      steps {
        git(url: 'https://github.com/EC501368/tes_app.git', branch: 'master', changelog: true)
      }
    }

  }
}