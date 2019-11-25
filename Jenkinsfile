pipeline {
    //agent any
    //agent none
    agent {
        label "Slave"
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building my first Jenkins build pipeline......'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing my first Jenkins Test pipeline......'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying my first Jenkins Deploy pipeline......'
            }
        }
    }
}
