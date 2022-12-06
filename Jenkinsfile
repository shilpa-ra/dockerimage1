pipeline {
    agent {label 'images'}
      stages {
        stage ('repo') {
            steps {
                git url: '',
                branch: 'main'
            }
        }
        stage ('docker img') {
            steps {
                sh 'sh docker.sh'
            }
        }
      }
}
