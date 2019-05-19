node{
	stage('get the code'){
		git 'https://github.com/jamesbonddd/test'
	}


	stage('clean, test, package the code'){
		def mvnHome =  tool name: 'maven-3', type: 'maven'
		sh "${mvnHome}/bin/mvn package"
	}
}