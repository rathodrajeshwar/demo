pipeline{
    agent:any
    stages{
       stage{"Git Checkout"}{
          steps{
              https://github.com/week9/leanmedia-packages.git
          
          }
       }
       stage{"creation of folder"}{
          steps{
              sh "cd mkdir file1"
         
          }
       }
stage{"Maven Build"}{
          steps{
              sh "mvn clean install"
    
          }
       }
