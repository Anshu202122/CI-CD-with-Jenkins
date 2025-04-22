pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Just a Simple build stage running."
                sh 'cat hello.txt'
            }
        }

        stage('Done') {
            steps {
                echo "Build complete. You can add more here later."
            }
        }
    }
}