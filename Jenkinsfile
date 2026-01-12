pipeline {
  agent any
  stages {
    stage('Clean') {
      steps {
           	bat 'mvn clean'
            echo "Clean success"    
      }
    }
    stage('Package') {
      steps {
           	bat 'mvn package'
            echo "Package success"    
      }
    }
    stage('Test') {
      steps {
           	bat 'mvn test'
            echo "Test success"    
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
}