node {
    def mvnHome = tool '/etc/alternatives/mvn'

    stage('Checkout') {
        checkout scm
    }

    stage('Build') {
        sh "${mvnHome}/bin/mvn -B package"
    }
}
