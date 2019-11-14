pipeline {
    agent any
    stages {
        stage('Build') {
		    steps {
		        withMaven(maven: 'maven-installation', mavenSettingsConfig: '2ec0c8bd-a1ff-4e2d-8be0-d069acf582c8') {
		            sh 'mvn -DskipTests clean package'
		        }
		    }
		}
    }
}