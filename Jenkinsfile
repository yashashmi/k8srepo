pipeline {
   agent any

   stages {
	  stage('DeploytoK8S') {
         steps {
			     script {
					     sh "kubectl apply -f ."
				}	
			}	
        }
    }
}

