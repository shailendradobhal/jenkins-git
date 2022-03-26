
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Jenkins"'
                sh '''
                    echo "This is a miltiline shell"
                    ls -lah
                '''
            }
        }
    }
}
