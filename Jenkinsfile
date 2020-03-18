pipeline {
  agent any
  stages {
    stage('Step1') {
      steps {
        build 'SampleBuildJob'
      }
    }

    stage('Step2') {
      steps {
        bat 'echo "Step2"'
      }
    }

  }
}