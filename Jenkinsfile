pipeline {
    agent any
    
   tools {
	 Maven 'Maven-3.9.12'
   }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
