pipeline {
    agent any
    stages {      
        stage('Building') {
            steps {
               echo 'Building.......'
                sh './hello.sh'
            }
        }

        stage('Testing') {
            steps {
               echo 'Testing.......'
            }
        }
    }
}
