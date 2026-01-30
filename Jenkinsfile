pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git branch:'master',url:'https://github.com/Akhila564905/devopslab1.git'
            }
        }
        stage('build')
        {
            steps
            {
                sh 'javac Hello.java'
            }
        }
        stage('run')
        {
            steps
            {
                sh 'java Hello'
            }
        }
    }
}
