pipeline{
  agent any
  tools{
    maven 'MAven'
  }
  stages{
    stage('GIT'){
      steps{
        git branch: 'main', url: 'https://github.com/bhanu4720/Docker-Bhanu.git'
      }
    }
    stage('Build'){
      steps{
        sh 'mvn clean install package'
      }
    }
    stage('Deploy to Tomcat'){
      steps{
        script{
          
        }
      }
    }
  }
}
