pipeline{

  agent { docker {image 'maven:3.3.3'} }
  stages{
   stage("Maven build"){
    steps{
 git 'https://github.com/csenapati12/rock-paper-scissors.git'
 sh 'ls -la'
 sh 'mvn -version'
 sh 'mvn clean install'
 }
   }
  }
}
