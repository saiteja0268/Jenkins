pipeline{
  agent any
  stages{
    stage('Checkout Code'){
      steps{
        git 'https://github.com/saiteja0268/Jenkins'
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
}
