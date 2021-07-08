pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                echo "VERSION: $VERSION"
            }
        }
        stage('Prepare build..') {
            steps {
                echo 'Prepare build'
                echo "VERSION: $VERSION"
            }
        }
        stage('Building application') {
            steps {
                echo 'Building application'
                echo "VERSION: $VERSION"
            }
        }
        stage('Testing..') {
            steps {
                echo 'Testing the build..'
                echo "VERSION: $VERSION"
            }
        }
        stage('Deploy..') {
            steps {
                echo 'Deployment in progress..'
                echo "VERSION: $VERSION"
            }
        }
    }
}
