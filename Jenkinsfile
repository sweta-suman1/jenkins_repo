pipeline {
    agent any

    tools {
        maven 'Maven3'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building using Maven'
                bat 'mvn package'
            }
        }
    }
}

