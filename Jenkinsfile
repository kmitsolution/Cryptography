pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build job is executed'
          }
        }

        stage('Build1.1') {
          steps {
            echo 'Build1.1 is executed'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Testing is successful'
      }
    }

    stage('Deployment') {
      steps {
        echo 'Deployment is done'
      }
    }

  }
}