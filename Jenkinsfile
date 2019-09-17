pipeline {
    agent any 
    stages {
        stage('---clean---') { 
            steps {
                sh "mvn clean"
            }
        }
        stage('---test---') { 
            steps {
                sh "/home/richard/javaTools/apache-maven-3.6.2/bin/mvn test"
            }
        }
        stage('---package---') { 
            steps {
                sh "/home/richard/javaTools/apache-maven-3.6.2/bin/mvn package" 
            }
        }
    }
}