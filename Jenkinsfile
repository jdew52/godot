pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'scons platform=linux'
            }
        }
    }
}
