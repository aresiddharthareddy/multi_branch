pipeline {
    agent any

    stages {
        stage('Third Branch - Info') {
            steps {
                echo "This is the Third Branch pipeline."
            }
        }

        stage('Run Python Script') {
            steps {
                bat 'python main.py'
            }
        }
    }
}
