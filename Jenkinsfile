pipeline{
  
  agent any
  
  stages{
    
    stage("build"){
      
      steps{
        
       sh 'python file1_main_code.py'
        
      }
      
    }
    
       stage("test"){
      
      steps{
        
        echo "this is test stage"
        
      }
      
    }
    
      stage("deploy"){
      
      steps{
        
        echo "this is deploy stage"
        
      }
      
    }
  
  }
  
}
