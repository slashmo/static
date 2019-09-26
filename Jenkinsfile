pipeline {
  agent any
  
  stages {
    
    stage('Lint HTML') {
        steps {
            ls -la
            echo 'Static Code Check...'
            sh 'tidy -q -e *.html'
        }
    }
    
  }
}
