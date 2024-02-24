pipeline {
    agent any



    stages {
        stage('Git') {
            steps {
                git 'https://github.com/amrutha2607/amrutha-feb23.git'
                sh 'java Demo.java'
                sh 'python3 main.py'
            }
        }
    }
}
