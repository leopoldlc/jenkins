/* Requires the Docker Pipeline plugin */
/* LASO Technologies Development */

pipeline {
    agent { docker { image 'python:3.10.7-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
