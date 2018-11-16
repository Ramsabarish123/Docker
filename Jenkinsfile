pipeline{
  agent none
  stages{
    stage('stage1'){
      agent {label "docker"}
      steps{
        script{
          docker.image('php:7').inside {
            // run your command
            sh "echo hello"
          }
        }
      }
    }
  }
}



