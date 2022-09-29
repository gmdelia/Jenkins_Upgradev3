pipeline{

      agent any
      stages{
            stage('Init'){
                  steps{
                        echo 'Hi, this is GMD'
                        echo 'Starting testing...'
                  }
            }
            stage('Build'){
                  steps{
                        echo 'Building maven project'
                  }
            }

            stage('Deploy'){
                  steps{
                        echo 'Deploying in staging area'
                  }
            }
      }

}