pipeline{
    agent any
    stages{
        stage('dev'){
            steps{
                echo "dev"
                python Test.py
            }
        }
        stage("staging"){
            steps{
                echo "staging"
            }
        }
        stage("prod"){
            steps{
                echo "prod"
            }
        }
    }
}
