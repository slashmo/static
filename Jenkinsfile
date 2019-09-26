pipeline {
    agent {
        docker {
            image 'ubuntu'
        }
    }
    stages {
        stage('Lint HTML') { 
            steps {
                echo 'Static Code Check...'
                sh 'tidy -q -e *.html'
            }
        }
    }
}
