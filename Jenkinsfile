pipeline {
  agent any
  environment {
    test_value = 'Hello!'
  }
  stages {
    stage("Brach Dev Step 1") {
      steps {
        sh 'echo "Step 1 Building...${test_value}"'
      }
    }
    stage("Brach Dev Step 2") {
      steps {
        sh 'echo "Step 2 Building...${test_value}"'
      }
    }
  }
}
