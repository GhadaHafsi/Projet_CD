pipeline {

  agent any

  stages {

    stage('Pull') {
     steps {
		script {
			checkout([$class: 'GITSCM', branches : [[name : '*/master']],
			userRemoteConfigs : [[
				credentialsId: 'e26bde46-c7f7-466d-88ec-976c14d5e199'
			url : 'https://github.com/GhadaHafsi/Projet_CD.git' ]]])
				
}


  }

}
