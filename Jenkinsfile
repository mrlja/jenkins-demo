pipeline {

  agent any

  stages {
    stage("build") {

       steps {
        sh ('echo building the application...')
      }
    }

    stage("test") {

      steps {
        sh ('echo testing the application...')
      }
    }

    stage("deploy") {

      steps {
        echo 'deploying the application...'
      }
    }

    }
  }