pipeline {
    agent any 
    stages {
        stage('Clean') { 
            steps {
                // 
                       bat '''cd C:\\Program Files (x86)\\Jenkins\\workspace\\MavenProject
mvn clean'''

                       

            }
        }
        stage('Test') { 
            steps {
                // 
                       bat '''cd C:\\Program Files (x86)\\Jenkins\\workspace\\MavenProject
mvn test'''

            }
        }
        stage('Deploy') { 
            steps {
                // 
                       bat '''cd C:\\Program Files (x86)\\Jenkins\\workspace\\MavenProject
mvn package'''

            }
        }
    }
}
