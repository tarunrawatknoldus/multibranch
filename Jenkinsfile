pipeline{
  agent any
  stages{
    stage ('clone') {
      steps{
        git branch: 'dev', url: 'https://github.com/tarunrawatknoldus/multibranch.git'
        }  
      }
    stage ('run') {
      steps{
        sh 'python3 dev.py'
        }
      }
  }
}
