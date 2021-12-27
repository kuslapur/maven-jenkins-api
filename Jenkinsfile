pipeline {
    agent any

    stages {
        stage('SCM checkout') {
            steps {
                git 'https://github.com/kuslapur/maven-jenkins-api.git'
            }
        }
        stage('Compile and package') {
            steps {
               sh 'mvn install'    
            }
        }    
    }
}
