
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building from GitHub'
                sh 'cat build.sh'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the project'
                sh 'test -f build.sh'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment simulation successful'
            }
        }
    }
}
