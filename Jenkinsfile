pipeline {
    agent any
    stages {
        stage('build') {
            steps {
				timeout(time: 1, unit: 'SECONDS'){
                	sh 'python --version'
            	}
            }
        }
    }
    post{
    	success{
    		echo 'SUCCESS!!!!!!JEJEJEJEJEJEJEJEJEEEEJ'
    	}
    	always{
    		echo 'BUILDING...'
    	}
    
    }
    
}
