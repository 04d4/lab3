/* groovylint-disable-next-line CompileStatic */
pipeline {
    tools {
        nodejs 'nodejs-7.8.0'
    }
    stages {
        stage('build') {
            steps {
                echo 'Building...'
                sh 'npm install'
            }
        }
        stage('test') {
            steps {
                echo 'Testing...'
                sh 'npm test'
            }
        }
    }
}
