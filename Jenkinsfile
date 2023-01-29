node {
  //Execute this Pipeline or any of its stages, on any available agent.
  //Defines the "Build" stage. stage blocks are optional in Scripted Pipeline syntax. 
  //However, implementing stage blocks in a Scripted Pipeline provides clearer visualization of each `stage’s subset of tasks/steps in the Jenkins UI.
  stage('Build') {
    steps {
      //Perform some steps related to the "Build" stage.
      echo "Stage Build triggered : %Date% : %Time%"
    }
  }
  //Defines the "Test" stage.
  stage('Test') {
    steps {
      //Perform some steps related to the "Test" stage.
      echo "Stage Test triggered : %Date% : %Time%"
    }
  }
  //Defines the "Deploy" stage.
  stage('Deploy') {
    steps {
      //Perform some steps related to the "Deploy" stage.
      echo "Stage Deploy triggered : %Date% : %Time%"
    }
  }
}