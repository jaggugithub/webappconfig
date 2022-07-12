pipeline {
    agent any
    stages {
        stage('Install Docker') {
            steps {
                sh 'ansible-playbook -i aws_ec2.yaml installdocker.yaml'
            }
        }
    }   
}