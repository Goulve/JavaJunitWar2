pipeline {
  agent none
  stages {
    stage('prepare') {
      agent any
      steps {
        git(url: 'git@github.com:Goulve/JavaJunitWar2.git', branch: 'master')
      }
    }

  }
}