pipeline {
	agent { label 'master' }
    stages {
        stage('Compilation') {
            steps {
                script {
					echo "test make"
					sh "make clean all"
					echo "make done2"
                }
            }
        }
	}
}
