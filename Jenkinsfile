pipeline {
    agent any

    environment {
        DOCKER_IMAGE = "dewyhorror26/devops-node-app"
        DOCKER_TAG = "latest"
    }

    stages {

        stage('Checkout Source') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/User12694/devops-project.git',
                    credentialsId: 'github-cred'
            }
        }

    }
}
