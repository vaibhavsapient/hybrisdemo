pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        sh '''cd ${workspace}/Code/hybris/bin/platform


. ./setenv.sh
ant clean all
'''
      }
    }
  }
}