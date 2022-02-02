pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''pwd
date'''
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'hello patel'
          }
        }

        stage('test 1') {
          steps {
            echo 'ha'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'ha moj ha'
        sleep 5
      }
    }

  }
}