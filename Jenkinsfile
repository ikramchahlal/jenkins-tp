pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/ikramchahlal/jenkins-tp', branch: 'main'
            }
        }
        
        stage('Compiler et exécuter HelloWorld') {
            steps {
                bat 'javac HelloWorld.java'
                bat 'java HelloWorld'
            }
        }
        
        stage('Compiler et exécuter Merci') {
            steps {
                bat 'javac Merci.java'
                bat 'java Merci'
            }
        }
        
        stage('Compiler et exécuter DeRien') {
            steps {
                bat 'javac DeRien.java'
                bat 'java DeRien'
            }
        }
    }
}
