pipeline {
    agent any

    stages {
        stage('Build / Test / Deploy') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
