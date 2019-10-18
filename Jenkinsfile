pipeline {
    agent any
    stages {
        stage('Git Clone') {
            git 'https://github.com/9rcrsz/testgitftp.git'
        }
        stage('ng version') {
            ng version
        }
    }
}
