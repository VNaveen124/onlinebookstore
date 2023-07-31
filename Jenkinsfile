pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Your build steps go here
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                // Your test steps go here
                sh 'mvn test'
            }
        }
        
    }
}
