pipeline {
  agent any
  stages {
    stage('Build and test') {
      steps{
        withMaven {
          sh 'mvn clean deploy -f invesdwin-norva/pom.xml -T4'
        }  
      }
    }
  }
}