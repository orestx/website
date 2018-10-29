pipeline {
    agent { 
			docker { 
				image 'php' 
				label 'docker'
			}
		}
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}

