pipeline {
    agent any
   
        stages {
        stage('Build2') {
            steps {
                echo 'Building2..'
            }
        }
        stage('Test2') {
            steps {
                echo 'Testing2..'
               }
        }
        stage('Deploy2') {
            steps {
                input 'The process is paused'
                echo 'Deploying2..'
            }
        }
    }
}
