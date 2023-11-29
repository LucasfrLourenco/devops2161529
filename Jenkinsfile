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
            docker info
            docker version
						docker compose version
						java --version
					'''
				}
    	}
    }
}