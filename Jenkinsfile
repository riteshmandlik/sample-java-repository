pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                def pom = readMavenPom file:'${workspace}/test/pom.xml'
                echp pom.version
            }
        }
    }
}