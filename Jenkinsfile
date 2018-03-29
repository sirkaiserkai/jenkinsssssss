pipeline {
    // String applicationName = "basic-app"
    // String buildNumber = "0.1.${env.BUILD_NUMBER}"
    // String goPath = "/Users/kai.johnson/go/src/${applicationName}"

    agent { docker { image 'golang:1.8.0-alpine' } }
    stage('Checkout from GitHub') {
        // No special needs here, if your projects relys on submodules the checkout step would need to be different
        checkout scm
    }
    stages {
        stage('build') {
            steps {

                sh 'go version'
                // sh "cd ${/} && GOOS=darwin GOARCH=amd64 go build -o binaries/amd64/${buildNumber}/darwin/${applicationName}-${buildNumber}.darwin.amd64"
                sh 'cd /go/src/github.com/sirkaiserkai/jenkinsssssss && go build'
                echo 'Success!'
            }
        }
    }
}