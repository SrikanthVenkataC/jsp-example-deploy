pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build Stage'
                mvn clean compile package
                }
        }
         stage('Deploy') {
            steps {
                echo 'Deploy'
                }
         }
         stage('Test') {
            steps {
                echo 'Test'
            }
        }
    }
}
