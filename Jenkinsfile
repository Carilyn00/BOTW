pipeline {
    agent any
    tools {
        maven 'Maven 3.6.3'
    }
    
    stages {
        stage ('Compile Stage') {
            steps {
                    echo 'Testing Compile'
                    sleep 60
            }    
         }
                          
        stage ('Testing Stage') {
           steps {
                 echo 'Testing Stage'
                 sleep 60
            }
         } 
       
       stage ('Deployment Stage') {
         steps {
                echo "Testing Deployment"
                sleep 60
         }
       }
    }    
}
