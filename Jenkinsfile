pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python --version'
      }
    }
    stage('time') {
      steps {
        bat 'python current_time.py'
      }
    }
  }
}
