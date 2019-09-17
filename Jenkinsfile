pipeline {
    agent any 
    stages {
        stage('---clean---') { 
            steps {
                sh "$MVN_HOME/bin/mvn clean"
            }
        }
        stage('---test---') { 
            steps {
                sh "$MVN_HOME/bin/mvn test"
            }
        }
        stage('---package---') { 
            steps {
                sh "$MVN_HOME/bin/mvn package" 
            }
        }
    }
}