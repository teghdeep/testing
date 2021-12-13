pipeline{
agent any
  stages{
  stage("git1") 
     {
      steps{
        git branch:'main', url:'https://github.com/teghdeep/testing.git'
      }
    }
    stage("copy")
          {
            steps{
               echo 'Copy..'
            }
          }
   
  }
  
  
}
