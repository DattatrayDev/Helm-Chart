pipeline {
    agent any
    stages {
        stage('helm install') {
            steps {
		    sh "helm install sample-application ."
            }
        }
    }
}
