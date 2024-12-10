pipeline{
    agent any
    stages{
        stage('build'){
            bat 'docker build my-todo-app .'
        }
        stage('run'){
            echo 'runnn'
        }
        stage('deploy'){
            echo 'deploy'
        }
    }
}