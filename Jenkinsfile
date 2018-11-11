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
        stage('1-US') {
          steps {
            echo 'deploy int'
          }
        }
        stage('2-UK') {
          steps {
            echo 'uk'
          }
        }
        stage('3-Canada') {
          steps {
            echo 'france'
          }
        }
        stage('4-France') {
          steps {
            echo 'germany'
          }
        }
        stage('5-[...]') {
          steps {
            echo 'germany'
          }
        }
      }
    }
    stage('Run Int Test') {
      parallel {
        stage('1-US') {
          steps {
            echo 'deploy int'
          }
        }
        stage('2-UK') {
          steps {
            echo 'uk'
          }
        }
        stage('3-Canada') {
          steps {
            echo 'france'
          }
        }
        stage('4-France') {
          steps {
            echo 'germany'
          }
        }
        stage('5-[...]') {
          steps {
            echo 'germany'
          }
        }
      }
    }
    stage('Create Stage Env') {
      parallel {
        stage('1-US') {
          steps {
            echo 'deploy int'
          }
        }
        stage('2-UK') {
          steps {
            echo 'uk'
          }
        }
        stage('3-Canada') {
          steps {
            echo 'france'
          }
        }
        stage('4-France') {
          steps {
            echo 'germany'
          }
        }
        stage('5-[...]') {
          steps {
            echo 'germany'
          }
        }
      }
    }
    stage('Create Test Data') {
      parallel {
        stage('1-US') {
          steps {
            echo 'deploy int'
          }
        }
        stage('2-UK') {
          steps {
            echo 'uk'
          }
        }
        stage('3-Canada') {
          steps {
            echo 'france'
          }
        }
        stage('4-France') {
          steps {
            echo 'germany'
          }
        }
        stage('5-[...]') {
          steps {
            echo 'germany'
          }
        }
      }
    }
    stage('Functional Test') {
      parallel {
        stage('1-US') {
          steps {
            echo 'deploy int'
          }
        }
        stage('2-UK') {
          steps {
            echo 'uk'
          }
        }
        stage('3-Canada') {
          steps {
            echo 'france'
          }
        }
        stage('4-France') {
          steps {
            echo 'germany'
          }
        }
        stage('5-[...]') {
          steps {
            echo 'germany'
          }
        }
      }
    }
    stage('Load Test') {
      parallel {
        stage('1-US') {
          steps {
            echo 'deploy int'
          }
        }
        stage('2-UK') {
          steps {
            echo 'uk'
          }
        }
        stage('3-Canada') {
          steps {
            echo 'france'
          }
        }
        stage('4-France') {
          steps {
            echo 'germany'
          }
        }
        stage('5-[...]') {
          steps {
            echo 'germany'
          }
        }
      }
    }
    stage('Tear Down Env') {
      parallel {
        stage('1-US') {
          steps {
            echo 'deploy int'
          }
        }
        stage('2-UK') {
          steps {
            echo 'uk'
          }
        }
        stage('3-Canada') {
          steps {
            echo 'france'
          }
        }
        stage('4-France') {
          steps {
            echo 'germany'
          }
        }
        stage('5-[...]') {
          steps {
            echo 'germany'
          }
        }
      }
    }
    stage('Deploy Prod') {
      steps {
        echo 'deploy'
      }
    }
  }
}