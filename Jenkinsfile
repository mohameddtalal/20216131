pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/<your-username>/bash-script-repo.git'
            }
        }
        stage('Execute Script') {
            steps {
                sh './list_files.sh'
            }
        }
    }
}
