pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage(' Hello World') {
      steps {
        echo "Hello ${MY_NAME}"
        sh 'java -version'
      }
    }
  }
}