node {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Build"
            }
		}
		stage('Test') {
            steps {
                echo "Test"
            }
		}
		stage('Integrationtest') {
            steps {
                echo "Integration test"
            }		
        }
    }
	post{
		always{
			echo 'Im awesome. I run always'
		}
		success{
			echo 'I run when you are successful'
		}
		failure{
			echo 'I run when you fail'
		}
	}
}




