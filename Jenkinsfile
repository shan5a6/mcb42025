def  myfn(a,b=100) {
  sum=a+b
  println "sum of ${a} & ${b} is, ${sum}"
}
pipeline {
  agent any 
  stages {
    stage('working with function') {
      steps {
        script {
          myfn(10,20)
          myfn(300,400)
          myfn(500)
        }        
      }
    }
  }
}
