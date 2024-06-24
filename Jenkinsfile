pipeline {
    agent any
    stages{
        stage('Build') {
            steps {
                echo "Building the code"
                bat 'mvn compile'
            }
        }
        stage('Test'){
            steps {
                echo "TEsting the code"
                bat 'mvn test'
            }

        }
        stage('Deploy'){
            steps {
                echo "Deploying the code"
            }
        }
    }
}
