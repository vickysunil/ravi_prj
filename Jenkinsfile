pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git "https://github.com/vickysunil/Docker-Project.git"
                sh "echo $BRANCH_NAME"
            }
        }
        stage('Goodbye') {
            steps {
                echo 'goodbye World'
            }
        }
    }
}
