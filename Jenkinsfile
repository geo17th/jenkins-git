pipeline {
    agent any
    stages {
        stage('SCM'){
            echo 'Gathering code from github'
        }
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
