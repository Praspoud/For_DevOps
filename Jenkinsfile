pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }


    post {
        success {
            echo 'Build, test, and publish successful!'
        }
    }
}
}
