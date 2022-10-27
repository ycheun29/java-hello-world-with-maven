pipeline {
  agent any
  stages {

    stage('Start') {
      steps {
        echo 'Start'
      }
    }
    
    stage('build maven project') {
      steps {
        sh '/usr/local/Cellar/maven/3.8.6/libexec/bin/mvn compile'
      }
    }

    stage('Package') {
      steps {
        sh '/usr/local/Cellar/maven/3.8.6/libexec/bin/mvn package'
      }
    }

    stage('Delivery....') {
      steps {
        echo 'The artifact is ready for delivery'
      }
    }

  }
}
