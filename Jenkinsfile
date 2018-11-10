pipeline {
  agent none
  stages {
    stage('Git Clone & Setup') {
      parallel {
        stage('1') {
          steps {
            echo 'clone'
          }
        }
        stage('') {
          steps {
            echo '1'
          }
        }
      }
    }
    stage('Build') {
      parallel {
        stage('2') {
          steps {
            echo 'build'
          }
        }
        stage('') {
          steps {
            echo '2'
          }
        }
      }
    }
    stage('Unit Test') {
      steps {
        echo 'unit test'
      }
    }
    stage('Code Quality') {
      steps {
        echo 'code quality'
      }
    }
    stage('Create Container') {
      steps {
        echo 'create container'
      }
    }
    stage('Version Container') {
      steps {
        echo 'version container'
      }
    }
    stage('Deploy to Int') {
      steps {
        echo 'deploy int'
      }
    }
    stage('Run Int Test') {
      steps {
        echo 'run int'
      }
    }
  }
}