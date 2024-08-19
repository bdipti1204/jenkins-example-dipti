pipeline {
  agent any
  stages {
    stage('hello Deepti Demo1') {
      steps {
        sh 'echo "Hello World from Deepti"'
        writeFile file: "uselessfile.md", text: "This file is useless, no need to archive it."
      }
    }
  }
}
