#!/usr/bin/env groovy

pipeline {
    
    agent {
        node {
            label 'my-defined-label'
            customWorkspace '/some/other/path'
        }
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'npm install'
            }
        }
        
      }
}
  
