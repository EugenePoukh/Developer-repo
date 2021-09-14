pipeline {
    agent any

    stages {
        stage('Copy') {
            steps { 
		        sh 'mkdir -p Web_files'
		        dir("Web_files"){
			        git branch: 'main',
			        credentialsId: 'f2eda0ea-493a-47d7-b78b-6f036f01a9f5',
			        url: 'git@github.com:EugenePoukh/Source-repo.git'           		}
	        }
        }
    
        
        stage('Build') {
            steps {
                sh 'ls -al Web_files'
            }
        }
       
    }
}


