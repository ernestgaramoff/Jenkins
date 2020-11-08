#!groovy

pipeline {
    agent { label 'master' }
    triggers { pollSCM('* * * * *') }
    tools {
        maven 'maven'
    }
        stage('clone') {
            steps {
                script {
                    sh "git@github.com:ernestgaramoff/Jenkins.git"
                }
            }
        }
}
