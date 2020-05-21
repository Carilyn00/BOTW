pipeline {
    agent any
    tools {
        maven 'Maven 3.6.3'
    }
    options {
      timeout(time: 60, unit: 'SECONDS') 
  }
    
    stages {
        stage ('Compile Stage') {
            steps {
                    echo 'Testing Compile'
            }    
         }
                          
        stage ('Testing Stage') {
           steps {
                 echo 'Testing Stage'
            }
         } 
       
       stage ('Deployment Stage') {
         steps {
                echo "Testing Deployment"
         }
       }
    }    
}
