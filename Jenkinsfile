pipeline {
    agent any
    stages {
        stage('Git Clone') {
            step {
                git 'https://github.com/9rcrsz/testgitftp.git'
            }
        }
        stage('ng version') {
            step {
                ng version
            }
        }
    }
}
