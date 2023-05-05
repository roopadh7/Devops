pipeline{
    agent any
        stages{
            stage('back-up jobs'){
                steps{
                    sh '''
                    cp -R /var/lib/jenkins/workspace /tmp
                    '''
                }
            }
        }
    }
