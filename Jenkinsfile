pipeline {
    agent any
    stages {
        stage('Git Clone') {
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
