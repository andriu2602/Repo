pipeline {
    agent any
	
    stages {
		
		
        stage('Build') {
            steps {
				
				bat 'cd C:/Users/fake2/Documents/RepoJenkins/java-tomcat-maven-example'				
				bat 'mvn -f  clean install'
                bat 'echo "Hello World lo logre"'

            }
        }
    }
}
