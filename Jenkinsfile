pipeline {
    agent {
        label "jenkins-agent"
    }
    tools {
    jdk 'java11'
    maven 'maven3'
    }

    }
    stages{
        stage("Cleanup Workspace"){
            steps {
                cleanWs()
            }

        }

        stage("Checkout from SCM"){
            steps {
                git branch: 'main', credentialsId: 'github', url: 'https://github.com/pankaj04101986/complete-prodcution-e2e-pipeline.git'
            }

        }
}

