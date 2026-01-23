pipeline {
    agent any
    stages {
        stage('CheckouT') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/ORG/REPO.git',
                    credentialsId: 'github-token'
            }
        }
    }
}
