pipeline {
    agent any
    stages {
        stage('Check SSH Connection Using Ping Module') {
            steps {
                sh 'ansible -i aws_ec2.yaml tag_Name_DockerServer -m ping'
            }
        }
        stage('Install Docker') {
            steps {
                sh 'ansible-playbook -i aws_ec2.yaml installdocker.yaml'
            }
        }
    }   
}