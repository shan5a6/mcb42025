def  myfn(a,b=100) {
  sum=a+b
  return(sum)
}
pipeline {
  agent any 
  stages {
    stage('working with function') {
      steps {
        script {
          myvalue=myfn(10,20)
          println "my return value is ${myvalue}"
        }        
      }
    }
  }
}
