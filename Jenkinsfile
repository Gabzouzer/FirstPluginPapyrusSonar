// Declarative //
pipeline {
	agent any
	stages {
		stage('Scan') {
			steps {
				echo 'Scan...'
				bat 'mvn sonar:sonar'
			}
		}
	}
}