pipeline {
    agent any
    stages {
        stage ('Parallel Staging') {
            parallel {
                stage('Unit Test') {
                    steps {
                        echo 'Unit Test Completed'
                        sleep 5
                    }
                }
                stage('Integration Test') {
                    steps {
                        echo 'Integration Test Completed'
                        sleep 5
                    }
                }
                stage('Security Test') {
                    steps {
                        echo 'Security Test Completed'
                        sleep 5
                    }
                }
            }
        }
    }
}