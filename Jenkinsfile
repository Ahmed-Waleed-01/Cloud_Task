pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
      	sh "chmod +x -R ${env.WORKSPACE}"
        sh './CloudTask.sh'
      }
    }
  }
}
