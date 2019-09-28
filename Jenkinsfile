#!groovy
pipeline {
  agent any

  environment {
    CHENQINGLIN = 'chenqinglin'
  }

  stages {
    stage('build') {
      steps {
        sh 'echo chenqinglin'
      }
    }
    stage('sanity check') {
      steps {
        input '你真的要继续执行吗'
      }
    }
    stage('cql') {
      steps {
        sh 'echo 车额'
        sh 'printenv'
      }
    }
  }
}