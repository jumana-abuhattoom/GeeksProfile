pipeline{

	agent any

	stages {
		stage('Build') {

			steps {
				sh 'sudo docker build -t jumanaah/geeksprofile:latest .'
			}
		}

		stage('Push') {

			steps {
				sh 'sudo docker push jumanaah/geeksprofile'
			}
		}
	}
}
