pipeline {
    agent any
    tools {
    	maven 'mvn-3.6.2'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}