pipelin {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'python3 hello.py'
            }
        }
        stage('Test') {
            steps {
                sh 'python3 test_hello.py'
            }
        }
        stage('Deploy') {
            steps {
                sh 'python3 deploy.py'
            
            }
        }
    }
}