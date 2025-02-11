pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/your-repository.git'
            }
        }
        stage('Build') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                bat 'java HelloWorld'
            }
        }
    }
}
