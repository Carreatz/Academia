pipeline {
    agent any
    stages {
        stage('download') {
            steps {
                sh '''
                ls
                echo "hola bola"
                '''
            }
        }
        stage('compilar') {
            steps {
                sh '''
                pwd
                echo "hola y tu"
                '''
            }
        }
        stage('deployar') {
            steps {
                sh '''
                echo "hola papu"
                '''
            }
        }
    }
}
