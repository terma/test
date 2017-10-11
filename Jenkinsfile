#!/usr/bin/env groovy

node {
  def scmVars = checkout scm
  
  stage('Printenv') {
    sh 'printenv'
  }
  
  stage('ScmVars') {
    echo scmVars
  }
}
