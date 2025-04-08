pipeline {
    agent any
    tools {
        maven 'Maven 3.8.6'
    }
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/your-repo/maven-project.git'  // Replace with your Git repo URL
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Add test commands here if needed'
            }
        }
    }
}
