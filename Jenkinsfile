#!groovy

node {
	   
	stage('Checkout'){

          git changelog: false, credentialsId: 'gitnew', poll: false, url: 'https://github.com/srini4547/maven-web-tomcat.git'

       }

       stage('BuildArtifact'){

         // sh 'mvn install'
	       
	       sh 'mvn clean'
       }
	   
      stage('Sonar') {
                    //add stage sonar
                   // sh 'mvn sonar:sonar'
                }
       
}
