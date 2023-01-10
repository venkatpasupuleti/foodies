pipeline {
    agent any
    stages {
        stage('checkout scm') {
            steps {
                echo 'pulling code from git repo'
            }
        }
        stage('build') {
            steps {
                echo 'building project using mvn'
            }
        }
    }
}