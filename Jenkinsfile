pipeline{
  agent any
  stages{
    stage('make files'){
      steps{
        sh "chmod +x ./scripts.sh"
        sh "./scripts.sh"
      }
    }
    stage('run script'){
      steps{
        sh "chmod +x ./helloWorld.sh"
        sh "./helloWorld.sh"
      }
    }
  }
}
