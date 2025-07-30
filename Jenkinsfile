pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repository...'
                // Example: git url: 'https://github.com/your-org/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
                // Example: sh 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example: sh 'mvn test'
            }
        }
    }
}
