pipeline {
  agent "slave1/java/docker/kubernetes"
  agent any 
  stages {
    stage('welcome note') {
      steps {
        script {
          println "welcome to dvs devops"
        }        
      }
    }
  }
}
