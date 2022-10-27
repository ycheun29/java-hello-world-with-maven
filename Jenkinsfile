pipeline {
  agent any
  stages {
    stage('build maven project') {
      steps {
        bat 'mvn compile'
      }
    }

    stage('Package') {
      steps {
        bat 'mvn package'
      }
    }

    stage('Delivery....') {
      steps {
        echo 'The artifact is ready for delivery'
      }
    }

  }
}
