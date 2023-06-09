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
        
        sh 'python file2_test_scripts.py'
        
      }
      
    }
    
      stage("deploy"){
      
      steps{
        
       sh 'python file3_deployment.py'
        
      }
      
    }
  
  }
  
}
