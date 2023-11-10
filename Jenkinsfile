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
}
