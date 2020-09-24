pipeline {
    agent {
       node {
           label '109'
       }
    } 
    stages {
        stage('Build') { 
            steps {
                sh "pwd"
            }
        }
        stage('Test') { 
            steps {
                sh "echo $PATH" 
            }
        }
        stage('Deploy') { 
            steps {
                println "OVER" 
            }
        }
    }
}
