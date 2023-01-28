pipeline {

  agent any
  
  tools {
      maven 'maven-3.8.6' 
  }
  
  stages {
  
    
    stage("build") {
    
      steps {
        sh "mvn clean install"
      }
    
    }
    
    stage("test") {
    
      steps {
        echo "testing out to the branch"
      }
    
    }
    
    stage("deploy") {
    
      steps {
        echo "deploying out to the branch"
      }
    
    }    
    
  
  }

}
