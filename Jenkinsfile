pipeline{
  agent any
  stages{
    stage('make files'){
      steps{
        sh "touch helloWorld.sh"
        sh "echo 'print(\\"hello world!\\")' > helloWorld.sh"
        sh "chmod +x helloWorld.sh"
      }
    }
    stage('run script'){
      steps{
        sh "./helloWorld.sh"
      }
    }
  }
}
