pipeline{

  agent { docker {image 'kennethreitz/pipenv'} }
  stages{
   stage("Maven build"){
    steps{
 git 'https://github.com/csenapati12/rock-paper-scissors.git'
 sh 'ls -la'
 sh 'pip test.py'
 
 }
   }
  }
}
