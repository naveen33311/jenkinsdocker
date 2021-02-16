//DECLARATIVE SCRIPT

pipeline { 
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Build"
            }
        }
        stage('Test') {
            steps {
                echo "Test"
            }
        }
        stage('Integration') {
            steps {
                echo "Integration"
            }
        }
    }
    post {
    always {
        echo "I'm awesome, I will always run"
        }
    failure {
        echo 'I run when you fail'
        }
}
}
