pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo 'Starting of the Build'
        sh '/bin/ksh starting_script.ksh'
        sleep 15
      }
    }

    stage('Test') {
      steps {
        echo 'Testing'
      }
    }

  }
}