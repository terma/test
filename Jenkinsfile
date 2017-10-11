#!/usr/bin/env groovy

node {
  checkout scm
  
        stage('Example') {
            steps {
                sh 'printenv'
                echo scm.toString()
            }
        }
}
