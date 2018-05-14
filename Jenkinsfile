node {
  stage('Run Ansible'){
  ansiblePlaybook become: true, becomeUser: 'ansadm', credentialsId: 'ansadmkey1', installation: 'MyAnsible', inventory: 'hosts', playbook: 'first.yml'
  }
}


