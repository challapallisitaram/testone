pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
			    echo 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
				echo 'npm start'
            }
        }
    }
}