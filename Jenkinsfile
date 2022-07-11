pipeline {
    agent any
        label 'ansible'
    stages {
        stage('Install Docker') {
            steps {
                sh 'ansible-playbook installdocker.yaml'
            }
        }
    }   
}