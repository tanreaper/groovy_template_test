#!/usr/bin/groovy
def agent_label = null
node('master') {
    stage('checkout and set agent') {
        echo "${env.ProjectId}"
    }
}

pipeline {
    agent {
        label "$AGENT_LABEL"
    }
}