pipeline {
  agent any

  stages { 
    stage('Checkout') {
      steps {
        git branch: 'main', url: 'https://github.com/champ886/jenkins_python_test.git'
            }
    }
    stage ('Build') {
      steps {
        sh './Helloworld.py'
      }
    }
  }
}
