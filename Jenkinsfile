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
                    echo "Trying to connect to Github repo"
                }
            }
        }
}
