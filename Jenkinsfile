pipeline {
  //Execute this Pipeline or any of its stages, on any available agent.
  agent any
  stages {
    //Defines the "Build" stage.
    stage('Build') {
      steps {
        //Perform some steps related to the "Build" stage.
        echo "Running Build"
        bat 'Build.bat'
      }
    }
    //Defines the "Test" stage.
    stage('Test') {
      steps {
        //Perform some steps related to the "Test" stage.
        echo "Running Test"
        bat 'Test.bat'
      }
    }
    //Defines the "Deploy" stage.
    stage('Deploy') {
      steps {
        //Perform some steps related to the "Deploy" stage.
        echo "Running Deploy"
        bat 'Deploy.bat'
      }
    }
  }
}
