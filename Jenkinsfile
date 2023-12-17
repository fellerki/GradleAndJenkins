pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    bat './gradlew.bat build'
                }
            }
        }
    }
}
