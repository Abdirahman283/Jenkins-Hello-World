pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    if (isUnix()) {
                        sh 'python3 hello.py'
                    } else {
                        bat 'python hello.py'
                    }
                }
            }
        }
    }
}
