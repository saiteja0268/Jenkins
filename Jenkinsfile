pipeline{
  agent any
  stages{
    stage('Checkout Code'){
      steps{
        git branch: 'main', url: 'https://github.com/saiteja0268/Jenkins.git'
      }
    }
    stage('Build'){
      steps{
        bat 'echo "Building the app"'
      }
    }
    stage('Test'){
      steps{
        bat 'echo "Running tests"'
      }
    }
    stage('Deploy'){
      steps{
        bat 'echo "Deploying"'
      }
    }
  }
  post{
    success{
      bat 'echo "Build Successful"'
    }
    failure{
      bat 'echo "Build Failed"'
    }
  }
}
