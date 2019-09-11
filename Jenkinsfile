pipeline{
	agent { node { label 'master' } } 
	stages{
		stage('Git Pull') {
		    steps{
		        sh label: '', script: '''docker build -t sumeetisp/docker-react .'''
		    }
		}
	}
}
