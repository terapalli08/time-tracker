pipeline 
{
    agent any
  stages 
    {
    stage ('build') 
        {
      steps 
            {
        sleep 100 
        echo 'this is build stage'
             }
      stage ('test') 
            {
        steps 
                {
          echo 'this is testing stage'
                 }
       stage ('deploy') 
                {
         steps 
                    {
           echo 'this is deploy stage'
          }
       }
      }
    }
   
          
