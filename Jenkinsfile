pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Completd'
      }
    }

    stage('Test2') {
      parallel {
        stage('Test2') {
          steps {
            echo 'Running test 2'
          }
        }

        stage('Test1') {
          steps {
            echo 'Running Test 1'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployement Completed'
      }
    }

    stage('finish') {
      steps {
        echo 'rinning finished'
      }
    }

  }
}