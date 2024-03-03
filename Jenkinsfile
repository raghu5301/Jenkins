pipeline{
    agent any

    stages{
        stage('Build'){
            steps{
                    agent {
                            label "slave1"
                    }
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