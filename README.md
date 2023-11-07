# Sample_scripted-pipeline-project
node {
     stage ('build')
     {
            echo "Building the project......."
            
     }
     stage ('Deploy')
     {
           echo "deploying the project......."
     
     }
     stage ('Testing')
     {
           echo "Testing the project........."
           
     }
     stage ('Release')
     {
           echo "Releasing the project......."
     
     }
     stage ('Deliver')
     {
           echo "Deliver the project........."

     }     
     
 }
      
      
