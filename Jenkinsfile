pipeline {
  agent any
  environment {
    name1 = "Jeff"
    name2 = "John"
  }
  stages {
    stage('Build'){
        environment {
            name3 = "Jamie"
        }
      steps {
        echo 'Hello World!'
        echo "name1 ${name1}"
        echo "name2 ${name2}"
        echo "name3 ${name3}"
      }
    }
  }
}
