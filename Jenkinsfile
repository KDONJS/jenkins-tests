pipeline {
  agent any
  tools {
    nodejs 'node-18.7.0'
  }

  options {
    timeout(time: 2, unit: 'MINUTES')
  }

  stages {
    stage('Install dependencies') {
      steps {
        sh 'cd C:/Users/yorli/Desktop/prueba && git clone https://github.com/KDONJS/jenkins-tests'
      }
    }
  }
}
