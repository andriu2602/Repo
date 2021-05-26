pipeline {
    agent any
	
    stages {
		
		stage('conection') {
		steps{
		git credentialsId: '166f5d56-43fd-4c19-9999-6720de690b1e', url: 'https://github.com/andriu2602/java-tomcat-maven-example.git'
		}
		}
        stage('Build') {
            steps {
				
							
				bat 'mvn clean install'
                bat 'echo "Hello World lo logre"'

            }
        }
    }
}
