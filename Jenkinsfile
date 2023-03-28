pipeline{
  agent any
  stages{
    stage ('clone') {
      steps{
        git branch: 'main', url: 'https://github.com/tarunrawatknoldus/multibranch.git'
        }  
      }
    stage ('run') {
      steps{
        sh 'python3 main.py'
        }
      }
  }
}
