pipeline {
  agent any

  stages {
    
      stage("complie") {
        steps{
          bat"javac hello.java"
        }
      }
      stage("run") {
        steps {
          bat"java hello"
        }
      }
  }
}
      
