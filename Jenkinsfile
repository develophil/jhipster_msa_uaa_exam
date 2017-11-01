#!/usr/bin/env groovy

properties([pipelineTriggers([githubPush()])])

node {
    
    stage('clean') {
        sh "chmod +x gradlew"
        sh "./gradlew clean --no-daemon"
    }

}
