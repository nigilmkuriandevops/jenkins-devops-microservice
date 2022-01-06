pipeline {
    //agent any
	agent { docker{ image 'node:13.8'} }
    stages {
        stage('build') {
            steps {
				sh 'node --version'
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




