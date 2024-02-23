#!/usr/bin/groovy
def agent_label = null
node('master') {
    stage('checkout and set agent') {
        echo "${env.ProjectId}"
    }
}

pipeline {
    agent any
    stages {
        stage('Just a checkpoint') {
            steps {
                script {
                    sh "echo Test"
                }
            }
        }
    }
}