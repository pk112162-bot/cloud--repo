pipeline {
agent any
stages {
stage('checkout') {
steps {
// checkout code form Git repository
   sh 'echo checking out'
  }
}
stage('Build') {
steps {
// Build the java application ( replace with your build commands)
  sh 'java version'
  }
}
stage('Deploy') {
steps {
// Deploy the application ( replace with your deployement commands)
  sh ' echo "Deploying the application" '
    }
  }
 }
}
