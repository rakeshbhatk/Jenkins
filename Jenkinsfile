pipeline {
  agent any
  stages {
    stage('Build Project') {
      steps {
        build 'SampleBuildJob'
      }
    }

    stage('Deploy Dev1') {
      parallel {
        stage('Deploy Dev1') {
          steps {
            bat 'echo "Deploying in Dev1"'
          }
        }

        stage('Deploy Dev2') {
          steps {
            bat 'echo "Deploying in Dev2'
          }
        }

      }
    }

  }
}