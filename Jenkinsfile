pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build completed'
      }
    }

    stage('test stages') {
      parallel {
        stage('teststahes') {
          steps {
            echo 'running teststages'
          }
        }

        stage('test1') {
          steps {
            echo 'run test 1'
          }
        }

      }
    }

    stage('debloy') {
      steps {
        echo 'd comletwd'
      }
    }

  }
}