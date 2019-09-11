pipeline{
	agent { node { label 'master' } } 
	stages{
		stage('Git Pull') {
		    steps{
		        git changelog: false, credentialsId: 'Sumeet', url: 'https://github.com/sumeetisp/docker-react.git'
		    }
		}
	}
}
