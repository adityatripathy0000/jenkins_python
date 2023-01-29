# Scripted syntax in Jenkinsfile

### Pipeline:
* A Pipeline is a user-defined model of a CD pipeline. A Pipeline’s code defines your entire build process, which typically includes stages for building an application, testing it and then delivering it.
* Also, a pipeline block is a key part of Declarative Pipeline syntax.

### Node:
* A node is a machine which is part of the Jenkins environment and is capable of executing a Pipeline.
* Also, a node block is a key part of Scripted Pipeline syntax.

### Stage:
* A stage block defines a conceptually distinct subset of tasks performed through the entire Pipeline (e.g. "Build", "Test" and "Deploy" stages), which is used by many plugins to visualize or present Jenkins Pipeline status/progress.

### Step:
* A single task. Fundamentally, a step tells Jenkins what to do at a particular point in time (or "step" in the process). For example, to execute the shell command make use the sh step: sh 'make'. 
* When a plugin extends the Pipeline DSL, that typically means the plugin has implemented a new step.

More details on : https://www.jenkins.io/doc/book/pipeline/
