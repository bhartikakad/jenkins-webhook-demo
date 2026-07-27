pipeline {

    agent {
        label 'linux-ubuntu'
    }

    stages {

        stage('Build') {
            steps {
                echo "Build started"
                sh "hostname"
            }
        }

        stage('Test') {
            steps {
                echo "Testing"
            }
        }

    }
}
