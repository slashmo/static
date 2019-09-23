pipeline {
  agent any
  
  stages {
    
    stage('Lint HTML') {
        steps {
            echo 'Static Code Check...'
            sh 'pwd'
            'ls -lh'
            sh 'tidy -q -e *.html'
        }
    }
    
  }
}
