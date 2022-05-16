pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Testing'
          }
        }

        stage('Parralell') {
          steps {
            echo 'running in parralel'
          }
        }

      }
    }

    stage('Build') {
      steps {
        echo 'Building'
      }
    }

    stage('Clean up ') {
      steps {
        echo 'cleaning'
      }
    }

  }
}