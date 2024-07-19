pipeline {
    
    agent any
    
    stages {
        stage('Checkout Source') {
            steps {
                git branch: 'main', url: 'https://github.com/Dhanashree-Shanbhag/Hello-world.git'
            }
        }
        stage('Build') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java HelloWorld'
                }
            }
        }
} 
