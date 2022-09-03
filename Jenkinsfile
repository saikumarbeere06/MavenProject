pipeline {
    agent any
	/*tools {
		maven 'MAVEN_HOME'
		jdk 'JAVA_HOME'
	}
	*/
	stages {
	    stage("Build") {
	      steps {
		     /* sh '''
		         echo "$PATH=${PATH}"
			 echo "MAVEN_HOME=${MAVEN_HOME}"
			 '''
			 */
		      sh 'mvn clean install'
		      echo "Building the application"
	      }
	    }
	    stage("Test") {
	      steps {
		      echo "Testing the application"
	      }
            }
	    stage("Deploy") {
	      steps {
		      echo "Deploying the application"
	    }
	}
	}
}
	        
	
	
			  
