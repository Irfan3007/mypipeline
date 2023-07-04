pipeline {
    agent any
    stages {
        stage('Code Pull') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Compile Stage') {
            steps {
                echo 'Hello Good Morning'
            }
        }
        stage('Testing Stage') {
            steps {
                echo 'Print Irfan'
            }
        }    
    }
    post {
        always {
            mail to: 'mirfanullah121@gmail.com',
            subject: "Pipeline success",
            body: "pipeline Result"
        }
    }
}
