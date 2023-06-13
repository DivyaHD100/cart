@Library('roboshop-shared-library') _
pipeline {
    agent any
    stages {

        stage('Performing Lint Check') {
                //when { branch pattern: "feature-.*", comparator: "REGEXP"}
                    steps {
                        script {
                            nodejs.lintchecks()
                        }


                    }
        }
        stage('Downloading the dependencies') {
            steps {
                sh "npm install"
            }
        
        }
    }
}
