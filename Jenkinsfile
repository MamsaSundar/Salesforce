pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        echo 'Migrate to QA'
      }
    }

    stage('QA') {
      steps {
        git(url: 'https://github.com/MamsaSundar/Salesforce', branch: 'master')
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy the changes'
      }
    }

  }
}