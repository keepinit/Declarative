pipeline {
  agent any
    stages {
        stage('Test') {
            steps { 
                    echo "Hello, This is my first pipeline"
                   }
               }
               
        stage('Test-Again'){
        
        steps {
                Input("Do you want to continue?")
              }
        }
      
    stage('Three') {
    when {
            not {
                 branch "master"
                }
     }
     
     steps {
     
        echo "Hello"
        
          }
        }
   
      }
   
   }                       
