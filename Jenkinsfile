//Jenkinsfile (Declarative Pipeline)
/* Requires the Docker Pipeline plugin */
pipeline {
    agent {
        label 'docker' 
    }
    agent { docker { image 'maven:3.9.0-eclipse-temurin-11' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
