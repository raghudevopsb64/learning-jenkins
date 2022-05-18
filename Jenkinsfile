pipeline {
  agent {
    node {
      label 'ansible'
    }
  }

  stages {

    stage('Test') {
      steps {
        echo 'Hello World'
      }
    }

    stage('Test1') {
      steps {
        echo 'Hello World'
      }
    }

  }

  post {
    always {
      echo 'OK'
    }
  }
}

//node {
//
//  stage('Test') {
//    echo 'Hello World'
//  }
//
//  stage('Test1') {
//    echo 'Hello World'
//  }
//
//}
