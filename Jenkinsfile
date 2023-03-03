pipeline {
    agent any
    tools {
    maven 'mvvn'
 }
    stages {
        stage('maven') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
