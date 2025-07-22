pipeline {
  agent any 

  stages {
        stage('Start App') {
            steps {
                echo 'Starting app...'
                  bat '''
                      dir
                      call npm ci
                      call npx vite
                  '''
              }
        }
    }
}
