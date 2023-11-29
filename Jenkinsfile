pipeline {
    agent any

    stages {
      stage('Iniciando'){
        steps {
          echo 'Iniciando Pipeline'
        }
      }
    	stage('DevOps') {
				steps {
					sh '''
						java --version
					'''
				}
    	}
    }
}