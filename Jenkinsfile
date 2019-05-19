node{
	stage('get the code'){
		git 'https://github.com/jamesbonddd/test'
	}


	stage('clean, test, package the code'){
		sh 'mvn package'
	}
}