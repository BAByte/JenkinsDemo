pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'gradle --version'
                sh 'gradle assemble'
                sh 'ls app/build/outputs/apk/'
            }
        }
    }
}