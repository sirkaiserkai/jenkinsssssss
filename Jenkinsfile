pipeline {
    // String applicationName = "basic-app"
    // String buildNumber = "0.1.${env.BUILD_NUMBER}"
    // String goPath = "/Users/kai.johnson/go/src/${applicationName}"

    agent { docker { image 'golang:1.8.0-alpine' } }
    stages {
        stage('build') {
            steps {

                sh 'go version'
                // sh "cd ${/} && GOOS=darwin GOARCH=amd64 go build -o binaries/amd64/${buildNumber}/darwin/${applicationName}-${buildNumber}.darwin.amd64"
                echo 'Success!'
            }
        }
    }
}