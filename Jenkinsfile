pipeline {
	agent any

	stages {
	    stage('Checkout') {
	        steps {
				checkout scm			        }
		    }
		stage('Build') {
	        steps {
//				sh '${MAVEN_HOME}/bin/mvn install'
				sh '/home/sindhu/Distors/apache-maven-3.5.4/bin/mvn install'
	        }
		}
	}
}
