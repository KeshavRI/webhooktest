pipeline {
    agent any

    stages {
        stage('deploy') {
            steps {
                sh "aws configure set region $AWS_DEFAULT_REGION"
                sh "aws s3 cp Code/index.html s3://my-static-bucket-jenkins"
            }
        }
    }
}
