pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                script {
                def pom = readMavenPom file:'./test/pom.xml';
                echo pom.version;
                }
            }
        }
    }
}