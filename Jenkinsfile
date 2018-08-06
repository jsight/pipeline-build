node {
	stage ('Build') {
		git url: 'https://github.com/jsight/pipeline-build.git'
		
		withMaven() {
			sh "mvn clean install"
		}
	}
}