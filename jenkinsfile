pipeline {
  agent any
  environments {
    test_value = 'Hello!'
  }
  stages {
    stage("Step 1") {
      steps {
        sh 'echo "Step 1 Building..."'
      }
    }
    stage("Step 2") {
      steps {
        sh 'echo "Step 2 Building..."'
      }
    }
  }
}
