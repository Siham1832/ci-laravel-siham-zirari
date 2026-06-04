pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                echo 'Repository cloned successfully'
            }
        }

        stage('Install Dependencies') {
            steps {
                echo 'Installing dependencies'
            }
        }

        stage('Laravel Check') {
            steps {
                sh 'php artisan --version'
            }
        }

        stage('Run Tests') {
            steps {
                echo 'Running tests'
            }
        }
    }
}
