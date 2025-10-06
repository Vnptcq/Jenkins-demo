pipeline {
  agent any
  stages {
    stage('Checkout'){ steps { checkout scm } }
    stage('Build')   { steps { sh 'echo "Build step here"' } }
    stage('Test')    { steps { sh 'echo "Run unit tests here"' } }
  }
}
