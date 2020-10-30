pipeline{
  agent python3
  stages{
    stage('make files'){
      steps{
        sh "touch helloWorld.py"
        sh "echo 'print('hello world!')' > helloWorld.py"
      }
    }
    stage('run script'){
      steps{
        sh python3 helloWorld.py
      }
    }
  }
}
