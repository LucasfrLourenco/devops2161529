pipeline {
    agent any

    stages {
      stage('Iniciando'){
        steps {
          echo 'Iniciando Pipeline'
        }
      },
    	stage('DevOps') {
				steps {
					sh '''
            docker version
						docker compose version
						java --version
            docker info
					'''
				}
    	}
    }
}