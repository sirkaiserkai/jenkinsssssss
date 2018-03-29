#!/usr/bin/env groovy

node('docker') {
    // String applicationName = "basic-app"
    // String buildNumber = "0.1.${env.BUILD_NUMBER}"
    // String goPath = "/Users/kai.johnson/go/src/${applicationName}"

    // stage('Checkout from GitHub') {
    //     checkout scm
    // }

    // stage("Create binaries") {
    //     docker.image("golang:1.8.0-alpine").inside("-v ${pwd()}:${goPath}") {
    //         for (command in binaryBuildCommands) {
    //             // build the Mac x64 binary
    //             sh "cd ${goPath} && GOOS=darwin GOARCH=amd64 go build -o binaries/amd64/${buildNumber}/darwin/${applicationName}-${buildNumber}.darwin.amd64"
    //             // build the Windows x64 binary
    //             sh "cd ${goPath} && GOOS=windows GOARCH=amd64 go build -o binaries/amd64/${buildNumber}/windows/${applicationName}-${buildNumber}.windows.amd64.exe"
    //             // build the Linux x64 binary
    //             sh "cd ${goPath} && GOOS=linux GOARCH=amd64 go build -o binaries/amd64/${buildNumber}/linux/${applicationName}-${buildNumber}.linux.amd64"
    //         }
    //     }
    // }
    stage("Echo stuff") {
        echo 'It worked!'
    }
    // stage("Archive artifacts") {
    // // Archive the binary files in Jenkins so we can retrieve them later should we need to audit them
    //     archiveArtifacts artifacts: 'binaries/**', fingerprint: true
    // }
}