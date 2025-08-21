def  myfn() {
  println "Hi all, welcome to dvs"
}
pipeline {
  agent any 
  stages {
    stage('working with function') {
      steps {
        script {
          myfn()
          myfn()
          myfn()
        }        
      }
    }
  }
}
