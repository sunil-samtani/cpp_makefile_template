pipeline {
	agent { label 'master' }
    stages {
        stage('Compilation') {
            steps {
                script {
					sh "make clean all"
                }
            }
        }
	}
}