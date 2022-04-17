pipeline{
 agent any
  stages{
    
    stage('verift git branch'){
      steps{
      echo "$bitBucketURL"
       sh "git clone -b $bitBucketBranch --single -branch $bitBucketURL"
      }
    }
    
    stage('verift git branch'){
      steps{
      echo "$GIT_BRANCH"
      }
    }
      
  }
  
}
