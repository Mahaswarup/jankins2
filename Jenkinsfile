pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/Mahaswarup/jankins2.git'
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
