pipeline {
    agent(label 'master')
    stages {
        stage('test') {
            agent(label 'devl')
            steps {
                def pom = readMavenPom file:'${workspace}/test/pom.xml'
                echp pom.version
            }
        }
    }
}