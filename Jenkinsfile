job("DSL_Project"){
  
  description("Test Automation Project Using Jenkins DSL")
  
  scm{
   git("https://github.com/harishchidere/Sample_RestAssured", "master") 
  }
  
  triggers{
   scm("* * * * *") 
  }
  
  steps{
  maven("package")
  }
  
  publishers{
   mailer("chidereharish@gmail.com") 
  }
  
}
