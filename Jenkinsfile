pipeline {
    agent any

    stages {
        stage('Final Branch - Info') {
            steps {
                echo "This is the Final Branch pipeline."
            }
        }

        stage('Run Python Script') {
            steps {
                bat 'python main.py'
            }
        }
    }
}
