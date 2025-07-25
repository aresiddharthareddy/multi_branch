pipeline {
    agent any

    stages {
        stage('Dev Branch - Info') {
            steps {
                echo "This is the Dev Branch pipeline."
            }
        }

        stage('Run Python Script') {
            steps {
                bat 'python main.py'
            }
        }
    }
}
