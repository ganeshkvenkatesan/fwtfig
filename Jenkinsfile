pipeline {
    agent any
    tools {
            maven 'Maven3' // Name of the Maven installation in Jenkins
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}

