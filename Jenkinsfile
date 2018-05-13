node {
  stage('Run Ansible'){
  def mvnHome = ansiblePlaybook installation: 'MyAnsible', inventory: 'hosts', playbook: 'first.yml'
  sh "${mvnHome}"
    
  }
}


