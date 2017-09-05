#!/usr/bin/env groovy

pipeline {
    agent none
    stages {
        stage('Build on FreeBSD') {
            agent { label 'freebsd' }
            steps {
                sh 'gmake'
            }
        }
    }
}
