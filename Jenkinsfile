pipeline {

    agent any

    stages {
        stage("Build") {
            steps {
                sh 'echo build'
            }
        }

        stage("run") {
            steps {
                sh 'python3 main.py'
            }
        }
    }
}
