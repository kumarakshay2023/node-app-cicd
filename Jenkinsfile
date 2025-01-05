pipeline{
    agent any
    stages{
        stage("installing the packages"){
            steps{
                sh "npm install"
            }
        }
        stage("running the application"){
            steps{
                sh "npm run dev"
            }
        }
    }
}
