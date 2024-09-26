pipeline {
  agent any

  stages {
    
      stage("Complie") {
        steps{
          bat"javac hello.java"
        }
      }
      stage("Run") {
        steps {
          bat"java hello"
        }
      }
  }
}
      
