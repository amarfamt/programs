pipeline {
  agent any
  stages {
    stage('myStage'){
      steps {
        echo 'Hello Success !Well Done Amar and Sanvi'
        sh 'ls -la' 
        sh 'date'
      }
    }
    stage('Build') {
      steps { 
        sh 'ls' 
      }
    }
  }
}

