#!/usr/bin/env groovy

node {
  checkout scm
  
  stages { 
        stage('Example') {
            steps {
                sh 'printenv'
                echo scm.toString()
            }
        }
    }
}
