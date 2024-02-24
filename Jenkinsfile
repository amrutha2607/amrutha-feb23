pipeline
	{
	agent any
	stages
		{
		stage("Git")
			{
			git  "https://github.com/amrutha2607/amrutha-feb23.git"
			}
			}
	stage("Run")
	{	
		steps
			{
			sh 'java Demo.java'
        
		}	
	}	
	stage("Run")
	{	
		steps
			{
			sh "python3 main.py"
			}	
		}	
	}
}
