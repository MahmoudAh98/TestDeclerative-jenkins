pipeline {
    agent any

    stages {
        stage('SCM Check out') {
            steps {
                echo "From github"
                sh "date"
            }
        }
        stage('Build') {
            steps {
                echo 'Build Completed'
            }
        }
        stage('Test') {
            steps {
                echo 'Test Completed'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Completed'
            }
        }
    }
}
