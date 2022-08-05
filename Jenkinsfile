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
        sh 'cd C:/Users/yorli/Downloads/platzi-scripts-master/platzi-scripts-master/jenkins-tests && npm i'
      }
    }
    stage('Run tests') {
      steps {
        sh 'cd C:/Users/yorli/Downloads/platzi-scripts-master/platzi-scripts-master/jenkins-tests && npm t'
      }
    }
  }
}
