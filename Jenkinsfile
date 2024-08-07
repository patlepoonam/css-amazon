pipeline {
	agent any
		
	stages {
	    stage('Checkout') {
	        steps {
			checkout scm			       
		      }}
		
		stage('Deployment'){
		   steps {
		sh 'cp target/amazon-css.war /home/poonam/Documents/Devops/apache-tomcat-9.0.82/webapps'
			}}	
}}
