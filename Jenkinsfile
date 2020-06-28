pipeline {
  agent any
    stage {
        stage('Test') {
            steps { 
                    echo "Hello, This is my first pipeline"
                   }
               }
               
        stage('Test-Again') {
        
        steps {
                Input("Do you want to continue?")
              }
        }
    stage('Three') {
    when   {
     not {
          brach "master"
          }
     }
     
     steps {
     
        echo "Hello"
        
        }
   }
   
   }
   
   }                       
