pipeline {
    agent any

    stages {
        stage('Copy') {
            steps { 
		sh 'mkdir -p Web_files'
		dir("Web_files"){
			git branch: 'main',
			 credentialsId: 'f2eda0ea-493a-47d7-b78b-6f036f01a9f5',				url: 'git@github.com:EugenePoukh/Developer-repo.git'           		}
		}
       
    stages {
        stage('Build') {
            steps {
<<<<<<< HEAD
                ls -al
=======
                sh "ls -l"
>>>>>>> f50c7f6d1fdacba2f98dd9ce9fc7a3bae00b4a8f
            }
        }
       
    }
}
}
}
