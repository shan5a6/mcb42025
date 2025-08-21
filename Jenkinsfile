pipeline {
  agent any 
  stages {
    stage('working with loops') {
      steps {
        script {
          for(i=1;i<=5;i++) {
            println "my i value is: ${i}"
          }
          lis1=["aws","azure","devops","aidevops"]
          for(ele in lis1) {
            println "my element is: ${ele}"
          }
          j=6
          while(j <= 10) {
            println "my j value is: ${j}"
            j=j+1
          }
        }        
      }
    }
  }
}
