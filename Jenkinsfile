pipeline {
    agent any
   
        stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
               }
        }
        stage('Deploy') {
            steps {
                input 'The process is paused'
                echo 'Deploying..'
            }
        }
    }
}
