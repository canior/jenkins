pipeline {
    agent any
    stages {
        stage('Run Script') {
            steps {
                script {
                    sh "/tmp/test.sh > /tmp/test.log"
                }
            }
        }
    }
}
