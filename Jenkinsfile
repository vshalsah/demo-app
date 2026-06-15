pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                bat 'javac Abc.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Abc'
            }
        }
    }
}