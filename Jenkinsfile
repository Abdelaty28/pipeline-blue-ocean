pipeline {
  agent any
  stages {
    stage('scm') {
      steps {
        echo 'hello world'
      }
    }

    stage('test') {
      parallel {
        stage('asd') {
          steps {
            echo 'running test'
          }
        }

        stage('test2') {
          steps {
            echo 'running test2 parllen '
          }
        }

      }
    }

  }
}