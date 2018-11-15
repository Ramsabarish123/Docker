pipeline{
agent none
stages{
stage('stage1'){
steps{
node('docker') {
  docker.image('php:7').inside {
    // run your command
    sh "phpunit"
  }
}
                                    
}
}
}
}



