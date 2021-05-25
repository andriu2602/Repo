pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo "Hello World lo logre"'
                bat '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
