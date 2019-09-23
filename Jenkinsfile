pipeline {
  agent any
  
  stages {
    
    stage('Lint HTML') {
        steps {
            echo 'Static Code Check...'
            pwd
            ls -lh
            sh 'tidy -q -e *.html'
        }
    }
    
  }
}
