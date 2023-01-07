pipeline {
    agent any
    stages {
        stage('Build'){
            steps {
                echo 'Build'
            }
        }
        stage('Test'){
            steps{
                echo 'Test'
            }
        }
        stage('Quality Gate - Sonar Qube'){
            steps{
                echo 'Sonar Qube'
            }
        }
        stage('Deploy to artifactory'){
            steps{
                echo 'Deploy to artifactory'
            }
        }
        stage('Deploy to QA '){
            steps{
                echo 'Deplot to QA'
            }
        }
        stage('Deploy to UAT'){
            steps{
                echo 'Deploy to UAT'
            }
        }
        stage('Deploy to staging '){
            steps{
                echo 'Deploy to staging'
            }
        }
        stage('Deploy to prod'){
            steps{
                echo 'Deploy to prod'
            }
        }
    }
    post {
        failure {
            echo 'failed'
        }
        success {
            echo 'success'
        }
        aborted {
            echo 'aborted'
        }
        always {
            echo 'always'
        }
    }
}