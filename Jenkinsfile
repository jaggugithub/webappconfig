pipeline {
    agent any
    stages {
        stage('Install Docker') {
            steps {
                sh 'ansible-playbook installdocker.yaml'
            }
        }
    }   
}