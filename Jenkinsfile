pipeline {

agent {
	label {
		label 'linux'
		customWorkspace "/home/ubuntu/rohit_data"
		}
		}
		
	stages {
		stage('continuous download') {
			steps {
					git credentialsId: '7', url: 'https://github.com/sachin93094/fusion.git'
					}
				}
				
		stage('checking status') {
			steps {
				echo 'git status'
				}
			}
		}
	}
