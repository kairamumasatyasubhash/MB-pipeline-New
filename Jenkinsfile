pipeline {
    agent any 
    stages {
        stage ('Build') {
            steps {
                echo "Welcome to jenkins Pipelines"
                 } 
             }
             post {
                always {
                    script {
                        def subject = "Job Status is: ${currentBuild.currentResult} "
                        def body = "Build Number is: ${currentBuild.number}\n" + "Status is: ${currentBuild.currentResult}\n" + "Job URL : ${env.BUILD_URL}"
                    }
                }
             }
        }
    }
