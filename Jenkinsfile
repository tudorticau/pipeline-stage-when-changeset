pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				changeset blob: "*.js"
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}