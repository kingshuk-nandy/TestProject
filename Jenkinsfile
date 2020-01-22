pipeline {
    agent any

     stages {
        stage('build') {
            steps {
                powershell 'java -version'
                powershell 'mvn --version'
            }
        }
    }
}