pipeline {
    agent {
	docker {
 	    image 'node:lts-bullseye-slim'
	    arg '-p 3000:3000'
	}
    }
     stages {
	  stage('Build') {
	      steps {
		  sh 'npm install'
	      }
	  }
     }
} 

