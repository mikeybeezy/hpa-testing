pipeline {

    }
    stages{
        stage('Deploy to kubernetes'){
            steps{
                script{
                    sh 'kubectl apply -f deploymentservice.yaml'


                }
            }
        }
    }
    
}