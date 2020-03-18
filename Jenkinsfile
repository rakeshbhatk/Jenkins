pipeline {
  agent any
  stages {
    stage('Build Project') {
      steps {
        build 'SampleBuildJob'
      }
    }

    stage('Step2') {
      steps {
        bat 'echo "Deploying in Dev1"'
      }
    }

  }
}