pipeline{
  agent any 
    stages{
      stage("build") {
        steps{
          echo 'Build the application...'
        }
      }

      stage("test"){
        steps{
          echo 'testing the application...'
        }
      }

      stage(deploy){
        stpes{
          echo 'deploying the application...'
        }
      }
    }
}
