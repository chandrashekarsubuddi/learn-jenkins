pipeline {

  agent {
    label 'ansible'
  }

  stages {

  stage('Hello') {
   steps {
      echo 'Hello World'
   }
  }

  stage('Hello') {
     steps {
        echo 'Hello World'
     }
    }

    stage('Hello') {
       steps {
          echo 'Hello World'
       }
      }

  }

  post {
    always {
      echo "sending mail"
    }
  }
}