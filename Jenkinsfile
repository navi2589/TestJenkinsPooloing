pipeline {
	agent any
	parameters{
		string(name:'Grettings', defaultValue:'Hellow', description:'How should i greet the world')
	}

	stages {
		stage('Example') {
			steps{
				echo "${params.Grettings} World..!!"
			}
			
		}
		
		stage('Build') {
			steps{
				echo "build World..!!"
			}
			
		}
	}

}

