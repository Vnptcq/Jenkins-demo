pipeline {
  agent any
  options { timestamps(); ansiColor('xterm') }
  stages {
    stage('Checkout'){ steps { checkout scm } }
    stage('Build')   { steps { sh 'echo "Build step here"' } }
    stage('Test')    { steps { sh 'echo "Run unit tests here"' } }
  }
}
