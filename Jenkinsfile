pipeline {
  agent none
  stages {
    stage('Git Clone & Setup') {
      steps {
        sh 'sh \'make\''
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