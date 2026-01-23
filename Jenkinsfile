pipeline {
    agent any
    stages {
        stage('Checkoutt') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/ORG/REPO.git',
                    credentialsId: 'my-pipline-rohan-github'
            }
        }
    }
}
