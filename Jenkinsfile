pipeline {
    agent any 
    stages {
        stage('...Executingclone...') { 
            steps {
                sh "mvn clean" 
            }
        }
        stage('Testing') { 
            steps {
                sh "mvn test"
            }
        }
        stage('Deploying') { 
            steps {
                sh "mvn package" 
           }
        }
    }
}
