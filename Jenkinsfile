pipeline {

  agent any

  stages {

    stage('Pull') {
      steps {
				git 'https://github.com/GhadaHafsi/Projet_CD.git'
			}
}
    
    stage('build'){
      steps {

          script{

          sh "ansible-playbook -vvv ansible/docker.yml -i ansible/inventory/host.yml -e ansible_become_password=ghalinour "
          }


    }
  }

  }
}
