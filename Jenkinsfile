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
        sh 'echo "hello World"'
      }
    }

  }
}