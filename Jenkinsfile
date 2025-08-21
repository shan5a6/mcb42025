pipeline {
  agent any 
  parameters {
    choice choices: ['dev', 'prod'], description: 'Choose the environment', name: 'ENV'
    string defaultValue: '1.0.0', description: 'Select the version', name: 'VERSION', trim: true
  }  
  environment {
    JAVA_HOME = "/usr/bin/java11"
  }  
  stages {
    stage('working with variables') {
      steps {
        script {
          subject = "jenkins-pipeline-scripting"
          batchno = 4
          println "my subject is ${subject},my batchno is ${batchno}"
          /* Consume default  variables */
          println 'my workspace  is ${WORKSPACE}'
          println "my build no is ${BUILD_NUMBER}"
          /* Consume values of parameters */
          println "my selected environment is ${params.ENV}"
          println "my selected version is ${params.VERSION}"
          /* Consume values of environment variables*/
          println "my java version is ${env.JAVA_HOME}"
        }        
      }
    }
  }
}
