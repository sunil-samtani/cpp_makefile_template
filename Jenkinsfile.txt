pipeline {
    agent { label "advazvm" }
    stages {
        stage('Preparation') {
            steps {
                script {
					sh "make clean all"
                }
            }
        }
	}
}