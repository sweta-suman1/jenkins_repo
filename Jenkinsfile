pipeline {
    agent any

    tools {
        maven 'Maven3'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building using Maven'
                bat '''
                mvn package ^
                -Dmaven.wagon.http.ssl.insecure=true ^
                -Dmaven.wagon.http.ssl.allowall=true
                '''
            }
        }
    }
}
