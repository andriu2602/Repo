pipeline {
    agent any
	environment {
                      PROJECT_ROOT = 'C:/Users/fake2/Documents/RepoJenkins/java-tomcat-maven-example'
		}
    stages {
		
		
        stage('Build') {
            steps {
				
				bat 'mvn -f ${PROJECT_ROOT} clean install'
                bat 'echo "Hello World lo logre"'

            }
        }
    }
}
