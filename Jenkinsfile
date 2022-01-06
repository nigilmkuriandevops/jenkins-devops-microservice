node {
	agents any
	stages{
		stage('Build') {
		            echo "Build"
	       }
		}
		stage('Test'){
			steps{
				echo"Test"

			}
		}
		stage('Integrationtest'){
			steps{
				echo"Integration Test"

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





