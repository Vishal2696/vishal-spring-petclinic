pipeline {
    agent any
    stages {
        stage('workspace cleanup') {
            steps {
                deleteDir()
            }
        }
        stage('Print statement') {
            steps {
                echo "Hello, This is output from pipeline job."
            }
        }
    }
}