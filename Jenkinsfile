#!/usr/bin/groovy
def agent_label = null


pipeline {
    agent any
    stages {
        stage('checkout and set agent') {
            steps {
                script{
                    echo "${env}"
                }
            }
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