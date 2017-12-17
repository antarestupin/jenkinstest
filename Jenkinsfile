pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('build') {
            steps {
                sh 'echo "hello there"'
                sh 'mvn --version'
                sh 'ls'
                sh 'ls -a'
            }
        }
    }
}
