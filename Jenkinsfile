node {
  //Execute this Pipeline or any of its stages, on any available agent.
  //Defines the "Build" stage. stage blocks are optional in Scripted Pipeline syntax. 
  //However, implementing stage blocks in a Scripted Pipeline provides clearer visualization of each `stage’s subset of tasks/steps in the Jenkins UI.
  stage('Build') {
    //Perform some steps related to the "Build" stage.
    echo "Running Build";
    bat 'Build.bat'
  }
  //Defines the "Test" stage.
  stage('Test') {
    //Perform some steps related to the "Test" stage.
    echo "Running Test";
    bat 'Test.bat'
  }
  //Defines the "Deploy" stage.
  stage('Deploy') {
    //Perform some steps related to the "Deploy" stage.
    echo "Running Deploy";
    bat 'Deploy.bat'
  }
}
