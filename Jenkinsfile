node {
	stage ('Build') {
		git url: 'https://github.com/jsight/pipeline-build.git'
		
		withMaven(maven: "maven3.5.4") {
			sh "mvn clean install"
		}
	}
}