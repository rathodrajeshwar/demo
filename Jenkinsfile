pipeline{
    agent:any
    stages{
       stage{"Git Checkout"}{
          steps{
              https://github.com/rathodrajeshwar/demo.git
          
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
