pipeline {
    agent any
    
    stages{
        stage ("Build Image"){
            steps {
                script {
                    dockerapp = docker.build("matheusmprado/sampletodoaula3:v${env.BUILD_ID}", '-f ./dockerfile .')
                }
            }
        }
    }
}