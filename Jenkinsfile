pipeline {

    agent any  // will run on any available agent
 
    stages {

        stage('Checkout') {

            steps {

                checkout scm

            }

        }
 
        stage('Build') {

            steps {

                echo "Building application..."
		echo "Trigger"

            }

        }
 
        stage('Test') {

            steps {

                echo "Running tests..."

            }

        }
 
        stage('Deploy') {

            steps {

                echo "Deploying app..."

            }

        }

    }

}
 
