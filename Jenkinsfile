pipeline{
  agent any

  stages {
    stage('build'){
      steps{
        git branch: 'master', url: "https://github.com/Ashwinkumar49/CI-CD_Demo.git"
      }
      }
    stage('deploy'){
      steps{
        sh 'cp -r * /var/www/html'
      }
    }
    }
  }
