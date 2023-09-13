pipeline {
	agent { 
		docker { image 'python_with_pytest:latest' }
	}
	

    stages {
        stage('Checkout') {
            steps {
				sh 'python3 -m pytest'
            }
        }
	}
}
