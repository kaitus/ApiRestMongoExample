pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps { //Checking out the repo
                git 'https://github.com/kaitus/ApiRestMongoExample.git'
            }
        }

        stage ('Build') {
            steps {
                bat 'mvn clean package' 
            }
        }
    }
}
