pipeline {
  agent any
  stages {
    stage('BUILD') {
      parallel {
        stage('BUILD') {
          steps {
            sh 'sh "mvn clean package"'
          }
        }

        stage('') {
          steps {
            sh 'sh "0completed"'
          }
        }

      }
    }

  }
  environment {
    MAVEN = '1'
  }
}