pipeline {
    agent {
       node {
           label '109'
           customWorkspace "${env.JOB_NAME}/${env.BUILD_NUMBER}"
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
