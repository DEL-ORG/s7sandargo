pipeline {
    agent any

    stages {
        stage('test') {
            steps {
                sh '''
                sleep 2
                ls
                pwd
                '''
            }
        }
        stage('validate') {
            steps {
                sh '''
                sleep 5
                ls 
                '''
            }
        }
        stage('scan') {
            steps {
                sh '''
                sleep 3
                ls
                pwd
                '''
            }
        }
        stage('build') {
            steps {
                sh '''
                sleep 3
                ls
                pwd
                '''
            }
        }
        stage('tag') {
            steps {
                sh '''
                sleep 3
                ls
                pwd
                '''
            }
        }
        stage('push') {
            steps {
                sh '''
                sleep 3
                ls
                pwd
                '''
            }
        }
        stage('deploy') {
            steps {
                sh '''
                sleep 3
                ls
                pwd
                '''
            }
        }
    }
}
