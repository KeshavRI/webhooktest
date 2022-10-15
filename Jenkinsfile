pipeline {
    agent any
pipeline {
    agent any
    stages {
        stage('deploy') {
            steps {
              sh "aws configure set region $AWS_DEFAULT_REGION" 
              sh "aws s3 cp index.html s3://webhook-demo1"
            }
        }
    }
}
}
