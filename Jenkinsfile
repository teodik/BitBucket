pipeline{
    agent any
    stages{
        stage('print a message'){
            steps{
                echo "webhook works let see"
            }
        }
        stage('Git status'){
            steps{
                script{
                    sh 'git remote -v'
                }
            }
        }
    }
}