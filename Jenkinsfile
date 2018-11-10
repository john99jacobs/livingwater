pipeline {
  agent none
  stages {
    stage('Git Clone & Setup') {
      steps {
        echo 'clone'
      }
    }
    stage('Build') {
      steps {
        echo 'build'
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
      parallel {
        stage('US') {
          steps {
            echo 'deploy int'
          }
        }
        stage('UK') {
          steps {
            echo 'uk'
          }
        }
        stage('Canada') {
          steps {
            echo 'france'
          }
        }
        stage('France') {
          steps {
            echo 'germany'
          }
        }
      }
    }
    stage('Run Int Test') {
      parallel {
        stage('US') {
          steps {
            echo 'run int'
            echo 'us'
          }
        }
        stage('UK') {
          steps {
            echo 'uk'
          }
        }
        stage('Canada') {
          steps {
            echo 'canada'
          }
        }
        stage('France') {
          steps {
            echo 'france'
          }
        }
      }
    }
  }
}