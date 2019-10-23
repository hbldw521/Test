pipeline {
  agent any
  stages {
    stage('bat') {
      steps {
        bat(script: 'mvn clean package', label: 'package')
      }
    }
    stage('print') {
      steps {
        echo 'test'
      }
    }
  }
}