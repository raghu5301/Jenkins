pipeline{
    agent any

    stages{
        stage('Build'){
            steps{
                    agent slave1
                    sh '''
                    ls -lrt
                    date
                    '''
            
            }
      
        }
        stage('Test'){
            steps{
                    sleep 20
            
            }
        }
    }
}