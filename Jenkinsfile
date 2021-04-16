pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "myslavemaven1"
            }
          
          steps {
             
                echo "my master branch"
          }
        }
   }
}
