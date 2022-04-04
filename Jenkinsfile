pipeline {
  agent any
  stages {
    stage('prepare') {
      agent any
      steps {
        git(url: 'https://github.com/Goulve/JavaJunitWar2.git', branch: 'master')
      }
    }

    stage('build') {
      agent any
      steps {
        sh 'mvn clean install'
      }
    }

  }
}