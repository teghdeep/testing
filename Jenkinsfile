pipeline{
agent any
  stages{
  stage("git") 
     {
      steps{
        git branch:'main', url:'https://github.com/teghdeep/testing.git'
      }
    }
    stage("copy")
          {
            steps{
               bat "cp index.html /var/www/html"
            }
          }
  }
  
  
}
