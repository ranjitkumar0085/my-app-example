node{
	stage('SCM Checkout'){
		git 'https://github.com/ranjitkumar0085/my-app-example.git'
	}
	stage('Compile-Package'){
		sh 'mvn package'
	}
}
