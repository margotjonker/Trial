pipeline {
    agent any
   
        stages {
        stage('Job1') {
            steps {
                echo 'Building2..'
            }
        }
        stage('Job2') {
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
