pipeline {
    agent any

    parameters {
            choice(name: 'ENV_GROUP', choices: ['dev', 'qa', 'ppe', 'integration', 'simulation1', 'regression'], description: 'Environment to deploy the VMs')
    }

    stages {
        stage()
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}