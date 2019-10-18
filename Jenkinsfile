pipeline {
    agent any
    stages {
        stage('Git Clone') {
            steps {
                git 'https://github.com/9rcrsz/testgitftp.git'
            }
        }
        stage('ng version') {
            steps {
                echo "Starting build ...."
                    sh '''#!/bin/bash
                          npm -v
                          ls -la
                          cd angular
                          ls -la
                          npm install
                          ng build --prod
                     '''
            }
        }
    }
}
