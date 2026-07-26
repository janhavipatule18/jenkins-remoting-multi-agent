pipeline {

    agent {
        label 'ubuntu-agent'
    }

    stages {

        stage('System Information') {
            steps {

                echo "Running Jenkins job on Ubuntu Agent"

                sh 'hostname'
                sh 'pwd'
                sh 'whoami'
                sh 'java -version'
                sh 'cat /etc/os-release'

            }
        }
    }

}
