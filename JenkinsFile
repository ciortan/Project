pipeline {
    agent any

    stages {
        stage('Production') {
            steps {
                git 'https://github.com/ciortan/Project.git'
                sh 'python3 test.py'
            }
        }
    }
}
