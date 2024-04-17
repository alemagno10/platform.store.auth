pipeline {
    agent any
    stages {
        stage('Jenkins Auth') {
            steps {
                echo 'Auth Service'
            }
        }
        stage('Build') { 
            steps {
                sh 'mvn clean install'
            }
        }      
    }
}