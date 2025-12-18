pipeline {
    agent any
    stages {
        stage('Run Ansible NetDevOps') {
            steps {
                sh '''
                cd Netdevops/ansible
                ansible-playbook -i inventory/hosts.yml site.yml
                '''
            }
        }
    }
}

