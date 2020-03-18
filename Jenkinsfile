pipeline {
  agent any
  stages {
    stage('Build Project') {
      steps {
        build 'SampleBuildJob'
      }
    }

    stage('Deploy Dev1') {
      steps {
        bat 'echo "Deploying in Dev1"'
      }
    }

  }
}