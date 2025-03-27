pipeline {
    agent any

    stages {
        stage("build") {
            steps {
                echo 'Building the application fast good'
            }
        }

        stage("test") {
            steps {
                echo 'Testing the application'
            }
        }

        stage("deploy") {
            steps {
                echo 'Deploying the application'
            }
        }
    }

    post {
        always {
            echo 'Cleaning up or sending notifications after the pipeline'
        }
    }
}
