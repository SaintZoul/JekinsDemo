pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'echo "Hello World!"'
				bat 'javac Main.java'
				bat 'java Main'
            }
        }
    }
}