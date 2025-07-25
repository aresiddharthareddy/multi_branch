pipeline {
    agent any

    stages {
        stage('Fourth Branch - Info') {
            steps {
                echo "This is the Fourth Branch pipeline."
            }
        }

        stage('Run Python Script') {
            steps {
                bat 'python main.py'
            }
        }
    }
}
