pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "step1"'
            echo 'step2'
          }
        }

        stage('Stage2') {
          steps {
            sh 'echo "step1 of stage2"'
          }
        }

      }
    }

  }
}