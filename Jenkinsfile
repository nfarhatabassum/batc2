pipeline {
    agent any
    stages{
        stage('Build') {
            steps {
                echo "Building the code"
                sh 'mvn compile'
            }
        }
        stage('Test'){
            steps {
                echo "TEsting the code"
                sh 'mvn test'
            }

        }
        stage('Deploy'){
            steps {
                echo "Deploying the code"
            }
        }
    }
}
