pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World 2"'
                sh '''
                    echo "Multiline shell steps works too - last last update "
                    ls -lah
                '''
            }
        }
    }
}
