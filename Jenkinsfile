node {
  stage('Run Ansible'){
  def mvnHome = ansiblePlaybook become: true, becomeUser: 'ansadm', credentialsId: 'ansadmkey1', installation: 'MyAnsible', inventory: 'hosts', playbook: 'first.yml'

  sh "${mvnHome}"
    
  }
}


