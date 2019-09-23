pipeline {
  agent any
  
  stages {
    
    stage('Lint HTML') {
        steps {
            echo 'Static Code Check...'
            sh 'pwd'
            sh 'ls -lh'
            sh 'tidy -q -e *.html'
        }
    }
    
  }
}
