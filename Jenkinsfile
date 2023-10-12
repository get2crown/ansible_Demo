pipeline{
  agent any  
  stages{  
      stage("Run ansible playbook"){
        steps{
        ansiblePlaybook credentialsId: 'Ansible_ssh-key', inventory: 'hosts', playbook: 'nginx_install.yaml'  
        }
      }
  }
}
