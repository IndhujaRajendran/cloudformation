pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name cluster1 --template-body file://Jenkins.json --region 'ap-south-1'"
              }
             }
            }
            }
