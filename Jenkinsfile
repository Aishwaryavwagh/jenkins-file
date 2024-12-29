pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', credentialsId: 'Aishwarya', url: 'https://github.com/Aishwaryavwagh/jenkins-file'
            }
        }
    }
}
