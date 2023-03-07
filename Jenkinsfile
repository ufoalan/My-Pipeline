//Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent {
        label 'docker' 
    }
    stages {
        stage('build') {
            agent { 
                      label 'docker' 
                      image 'maven:3.9.0-eclipse-temurin-11'
                  }
            steps {
                sh 'mvn --version'
            }
        }
    }
}
