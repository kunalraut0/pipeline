pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'mvn clean package'
      }
    }

    stage('test') {
      steps {
        echo 'test successful'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy successful;'
      }
    }

  }
}