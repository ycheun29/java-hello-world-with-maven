pipeline {
  agent any
  stages {
    stage('build maven project') {
      steps {
        sh 'mvn compile'
      }
    }

    stage('Package') {
      steps {
        sh 'mvn package'
      }
    }

    stage('Delivery....') {
      steps {
        echo 'The artifact is ready for delivery'
      }
    }

  }
}
