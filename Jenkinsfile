pipeline {
    agent any
    stages {
        stage('Git Clone') {
            steps {
                git 'https://github.com/9rcrsz/testgitftp.git'
            }
        }
        stage('ng') {
            steps {
                npm -v
            }
        }
    }
}
