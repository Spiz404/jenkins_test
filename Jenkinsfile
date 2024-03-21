pipeline {

    agent any

    stages {
        stage("Build") {
            steps {
                sh 'echo build'
            }
        }

        stage("run") {
            sh 'python main.py'
        }
    }
}
