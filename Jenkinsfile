
node {
  
   
   stage('SCM Checkout'){
	   git 'https://github.com/gkmvit/my-app-1'
   }
	
   stage('Compile Package')
	{
		
	   def mvnhome = tool name: 'maven-3', type: 'maven'
		sh "${mvnhome}/bin/mvn package"
  
	}
   }
   
