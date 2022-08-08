pipeline{

	agent any

	stages {
		stage('Build') {

			steps {
				sh 'sudo docker build -t jumanaah/geeksproject:latest .'
			}
		}

		stage('Push') {

			steps {
				sh 'sudo docker push jumanaah/geeksproject'
			}
		}
	}
}