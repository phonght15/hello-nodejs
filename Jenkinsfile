pipeline {
    agent any

    stages {
        stage('Say Hello') {
            steps {
                echo 'Hello Phong'
            }
        } 
           
        stage('Read File'){
            steps {
                sh 'cat code.txt'
            }
        }    
    }
}