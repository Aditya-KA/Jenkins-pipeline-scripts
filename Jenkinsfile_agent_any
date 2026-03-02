pipeline {
    agent any
    
    stages {
        stage('stage-1') {
            steps {
                echo "this is stage one"
                sh "uptime"
            }
        }

        stage('stage-2') {
            steps {
                echo "this is stage two"

                sh ''' 
                ls -lrt
                df -h
                '''
            }
        }
    }
}