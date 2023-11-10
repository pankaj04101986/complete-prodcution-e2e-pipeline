pipeline {
    agent {
        label "jenkins-agent"
    }
    tools {
    jdk 'java11'
    maven 'maven3'
    }

    stages {
        stage('clean workspace') {
            steps {
                cleanWs{}
            }
        }
        
        }
        
        stage('git checkout') {
            steps {
                git branch: 'main', CredentialsID: 'github', url: 'https://github.com/pankaj04101986/complete-prodcution-e2e-pipeline.git'
            }
    }
}

