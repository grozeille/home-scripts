pipeline {
    agent any

    stages {
        stage('Run') {
            steps {
                checkout scm
                echo 'Run'
                sh 'python ./hello.py'
            }
        }
    }
}