pipeline {
    agent {
        label '109'
    }
    stages {
        stage('Build') { 
            steps {
                sh "pwd"
            }
        }
        stage('Test') { 
            steps {
                sh "echo ${JAVA_HOME}" 
            }
        }
        stage('Deploy') { 
            steps {
                println "OVER" 
            }
        }
    }
}
