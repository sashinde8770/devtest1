pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh '''echo "welcome" > file6
'''
          }
        }

        stage('test') {
          steps {
            echo 'testing'
          }
        }

      }
    }

  }
}