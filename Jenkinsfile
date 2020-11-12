#!groovy

pipeline {
    agent any
    stages{
        stage('clone') {
            steps {
                sh 'docker build -t  project_template/Dockerfile'  
            }
        }
    }
}
