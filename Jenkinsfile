pipeline {
  agent any
  
  stages {
    
    stage('Lint HTML') {
        steps {
            apt-get install tidy
            echo 'Static Code Check...'
            sh 'tidy -q -e *.html'
        }
    }
    
  }
}
