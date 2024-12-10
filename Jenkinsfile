pipeline{
    agent any
    stages{
        stage('build'){
          steps{

           bat 'docker build -t my-todo-app .'
          }
        }
        stage('run'){
            
            steps{
                echo 'runnn'
        }
        }
        stage('deploy'){
          steps{

          
            echo 'deploy'
          }
        }
    }
}