
pipeline {
    agent any
    environment {
        AWS_ACCESS_KEY_ID     = credentials('test')
    }
    stages {
        stage('Example') {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
                echo "aws key $AWS_ACCESS_KEY_ID done"
            }
        }
    }
}
