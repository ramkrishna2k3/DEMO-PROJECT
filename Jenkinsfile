pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Ram from Calsoft
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
            stage('Deploy Prod') {
                  steps {
                        echo "Deploying in Prod Area"
                  }
            }
      }
}
