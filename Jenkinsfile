pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking the code from Github'
                agit branch: 'aws_code_deploy_pipeline_test', credentialsId: 'GIT_JENKINS', url: 'https://github.com/PriyankaJC2697/petclinic.git'
            }
        }
    }   
}
