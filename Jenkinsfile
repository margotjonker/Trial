pipeline {
    agent any

    node {
    git url: 'https://github.com/margotjonker/Trial.git'
    bat "git status"}
    
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
                echo 'Deploying....'
            }
        }
    }
}
