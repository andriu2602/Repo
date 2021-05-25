pipeline {
    agent any
	environment {
                      PROJECT_ROOT = 'C:/Users/fake2/Documents/RepoJenkins/java-tomcat-maven-example'
		}
    stages {
		
		
        stage('Build') {
            steps {
				echo "PATH=${PROJECT_ROOT}"
				bat 'cd ${PROJECT_ROOT}'				
				bat 'mvn -f  clean install'
                bat 'echo "Hello World lo logre"'

            }
        }
    }
}
