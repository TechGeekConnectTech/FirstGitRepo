pipeline {
    agent any
    stages{
        stage('Build'){
            steps{
                echo "Im building Project from Git "
                echo "Build Number - ${env.BUILD_NUMBER}, Branch Name - ${env.BRANCH_NAME}, JOB_URL - ${env.JOB_URL}"
            }
        }
        stage('Test'){
            steps{
                echo "I'm in testing"
            }
        }
        stage('Deploy'){
            steps{
                echo "I'm now in deployment stage"
            }
        }
    }
}
