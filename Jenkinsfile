pipeline {
    agent any

    tools {
        maven 'Maven3'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building using Maven'
                sh 'mvn clean package'
                // bat 'mvn clean package'  // Windows
            }
        }
    }
}
