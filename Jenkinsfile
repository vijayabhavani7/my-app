
node {
   stage('SCM Checkout'){
    // Clone repo
	 git 'https://github.com/javahometech/myapp'
   }
	stage('compile-package'){
		def mvnHome = tool name: 'maven-3', type: 'maven'
		sh "$(mvnHome}/bin/mvn package"
	}
}	
   
   
  
