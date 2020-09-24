pipeline {
    agent {
       label '109'
    } 
    stages {
        stage('Build') { 
            steps {
                println "Build" 
            }
        }
        stage('Test') { 
            steps {
                sh "echo $PATH" 
            }
        }
        stage('Deploy') { 
            steps {
                println "Deploy" 
            }
        }
    }
}
