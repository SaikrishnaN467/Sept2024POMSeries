pipeline{

	agent any
	stages{
		stage("build"){
			steps{
				echo("buils the project")
		}
	}
	stage("Run Uni test"){
		steps{
			echo("run UTs")
		}
	}
	stage("Run Integration test"){
		steps{
			echo("run ITs")
		}
	}
	stage("Deploy to dev"){
		steps{
			echo("deploy to dev")
		}
	}
	stage("Deploy to QA"){
		steps{
			echo("deploy to QA")
		}
	}
	stage("Run regression test cases on QA"){
		steps{
			echo("Run test cases on QA")
		}
	}
	stage("Deplo to stage"){
		steps{
			echo("deploy to stage")
		}
	}
	stage("Run sanity test cases on Stage"){
		steps{
			echo("Run sanity test cases on Stage")
		}
	}
	stage("Deplo to PROD"){
		steps{
			echo("deploy to PROD")
		}
	}
    }
  }