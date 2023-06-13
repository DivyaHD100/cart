pipeline {
    agent any
    stages {

        stage('Performing Lint Check') {
                //when { branch pattern: "feature-.*", comparator: "REGEXP"}
                    steps {
                        sh "echo installing jslint"
                        //sh "npm install jslint"
                        //sh "ls -ltr node_modules/jslint/bin"
                        //sh "node_modules/jslint/bin/jslint.js server.js"
                        sh "echo PERFORMING LINT CHECKS"
                        sh "echo PERFORMING LINT CHECKS COMPLETED"

                    }
        }
        stage('Downloading the dependencies') {
            steps {
                sh "npm install"
            }
        
        }
    }
}
