pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "kubepod"
            }
          
          steps {
             
                echo "my master branch"
          }
        }
   }
}
