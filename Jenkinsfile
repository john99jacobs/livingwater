pipeline {
  agent none
  stages {
    stage('1') {
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