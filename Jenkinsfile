node {
	agents any
	stages{
		stage(build){
			steps{
				echo"Build"

			}
		}
		stage(test){
			steps{
				echo"Test"

			}
		}
		stage(integrationtest){
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

}



