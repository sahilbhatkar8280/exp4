pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'javac Hello.java'
            }
        }
        stage('world') {
            steps {
                bat 'java Hello'
            }
        }
    }
}
