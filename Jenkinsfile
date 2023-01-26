pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'This is first build'
            }
        }
        stage('Pre-Test') {
            steps { 
                echo 'We are doing a pre-test before main test job'
            }
        }
        stage('Test') {
            steps {
                echo 'This is testing of our job '
            }
        }
    }
}
