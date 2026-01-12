pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
           // bat 'mvn clean package'
            echo "build success"    
      }
    }
 
    stage('Test') {
      steps {
          //bat 'mvn test -Dmunit.test=employee-ws-suite.xml#employee-wsFlow-test'
          echo "test success"
      }
    }
    stage('Run') {
      steps {
          //bat 'curl -ik http://localhost:8086/customer'
          echo "run success"
      }
    }
 
     stage('Deploy Development') {
      steps {
            //bat 'mvn deploy -DmuleDeploy'
            echo "deploy success"           
      }
    }
}
 
 