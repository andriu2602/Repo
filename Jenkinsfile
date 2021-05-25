pipeline {
    agent any
	
    stages {
		
		
        stage('Build') {
            steps {
				
				bat 'cd C:/Users/fake2/Documents/RepoJenkins/java-tomcat-maven-example/src/main/webapp'				
				bat 'mvn clean install'
                bat 'echo "Hello World lo logre"'

            }
        }
    }
}
