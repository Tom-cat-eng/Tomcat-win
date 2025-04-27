pipeline {
    agent any
    stages {
        stage ("Stage 1") {
            steps{
                echo "This is stage 1"
            }
        }
        stage ("Stage 2") {
            steps {
                echo "This is stage 2"
            }
        }
        stage ("Stage 3") {
            steps {
                echo "This is stage 3"
            }
        }
    }
    post {
        always {
            emailext body: 'Ran successfully', subject: 'Sample Mail ', to: 'pugals976@gmail.com'
        }
    }

}
