pipeline {
    agent any
    stages {
        stage('Run Script') {
            steps {
                script {
                    sh "sudo /tmp/test.sh > /tmp/test.log"
                }
            }
        }
    }
}
