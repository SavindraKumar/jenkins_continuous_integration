pipeline {
    agent any 
    stages {
        stage('Static Analysis') { 
            steps {
                echo 'Static Analysis'
            }
        }
        stage('Build') { 
            steps {
                gcc main.c -o main
            }
        }
        stage('Unit Test') { 
            steps {
                echo 'Unit Test'
            }
        }
        stage('Code Coverage') { 
            steps {
                echo 'Code Coverage'
            }
        }
    }
}
