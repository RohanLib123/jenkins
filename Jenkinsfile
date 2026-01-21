pipeline{
  agent any 
  stages{
    stage("build") {
      steps{
        echo 'Build the application...'
        script{
          def test = 2 + 2 > 3 ? 'cool' : 'not cool'
          echo test
        }
      }
    }

    stage("test"){
      steps{
        echo 'testing the application...'
      }
    }

    stage("deploy"){
      steps{
        echo 'deploying the application...'
      }
    }
  }
}
