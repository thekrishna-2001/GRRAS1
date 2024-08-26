pipeline{
	agent any
	stages{
		stage(checkout){
			steps{
			git 'https://github.com/thekrishna-2001/GRRAS1.git'
			}
		}
		stage(build){
			steps{
				sh 'mvn install'
			}
		}
		stage(deploy){
			steps{
				sh 'cp target/GRRAS1.war /home/krishna/Documents/Devops/apache-tomcat-9.0.93/webapps'
		}
			}
		}
	}
