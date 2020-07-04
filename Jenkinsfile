pipeline
{
agent any
  stages
  {
    stage('git clone')
    { steps
     {sh 'echo downloading code'}
    }
    
    stage('Code Build')
      { steps
     {sh 'echo Code is building'}
    }
    
    stage('get approvals')
    {steps
     {input "Please approve the deployment?"}
    }
    
    stage('Code Deploy')
      { steps
     {sh 'echo Code is Deployed'}
    }
    
  }
  
}
