pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build comblited'
      }
    }

    stage('test stage') {
      parallel {
        stage('test1') {
          steps {
            echo 'test combilited'
            retry(count: 3) {
              sh '''dtydydtrt
'''
            }

          }
        }

        stage('test2') {
          steps {
            echo 'running test2 parllen '
          }
        }

      }
    }

    stage('deploy') {
      steps {
        input(message: 'are you sure to move the next step?', ok: 'yes,iam sure')
      }
    }

    stage('notfiy ') {
      steps {
        echo 'notify me this pipeline end succesfuly'
      }
    }

  }
}