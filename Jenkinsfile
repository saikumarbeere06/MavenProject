pipeline {
    agent any
	tools {
		maven 'MAVEN_HOME'
	}
	stages {
	    stage("Build") {
	      steps {
		      sh 'mvn --version'
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
	        
	
	
			  
