pipeline 
{
	agent any
	stages {
    		stage('git clone'){
      			steps{
      			 git url: 'https://github.com/Nitzzz7/game-of-life-org.git'
           		     }
                                }		   
		stage('clean'){
			steps{
				sh 'mvn clean'
			     }
		               }
		stage('compile'){
			steps{
				sh 'mvn compile'
			}
		}
	      }
}	
