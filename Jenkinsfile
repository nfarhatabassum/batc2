pipeline {
    agent any
    stages{
        stage('Build') {
            steps {
                echo "Building the code"
                script 'mvn compile'
            }
        }
        stage('Test'){
            steps {
                echo "TEsting the code"
                script 'mvn test'
            }

        }
        stage('Deploy'){
            steps {
                echo "Deploying the code"
            }
        }
    }
}
