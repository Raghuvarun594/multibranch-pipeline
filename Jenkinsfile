pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'uptime' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "this is sravan proj..."'
        }
      }

         stage("Deploy nodejs application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
