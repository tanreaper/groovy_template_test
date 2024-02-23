#!/usr/bin/groovy
def agent_label = null


pipeline {
    agent any
    stages {
        stage('checkout and set agent') {
            echo "${env.ProjectId}"
        }
        stage('Just a checkpoint') {
            steps {
                script {
                    sh "echo Test"
                }
            }
        }
    }
}