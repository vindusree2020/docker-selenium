//variables
def network='jenkins-${BUILD_NUMBER}'
def seleniumHub='selenium-hub-${BUILD_NUMBER}'
def chrome='chrome-${BUILD_NUMBER}'
def firefox='firefox-${BUILD_NUMBER}'
def containertest='conatinertest-${BUILD_NUMBER}'
   
pipeline {
  
   agent any
   
   stages { 

	  /*stage('Code Checkout') {
            			steps {
                	git 'https://gitlab.com/vindusree2020/docker-selenium-jenkinsfile-master.git'	
				}
			}*/
      stage('Build Jar') {
            steps {
                sh 'mvn clean package -DskipTests'

   
      
}
}
   }}
