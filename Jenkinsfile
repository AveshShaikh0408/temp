pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
             def command = "aws cloudformation create-stack --stack-name s3bucket --template-body file://simplests3cft.json --region 'us-east-1'"
            command.execute()
              }
             }
            }
            }
