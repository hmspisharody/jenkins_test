pipeline {
    agent any
    stages {
        stage('myStage'){
            steps {
                bat 'dir' 
                bat 'echo "There are files">>new.txt'
            }
        }
        stage('Build') {
            steps { 
                bat 'dir' 
            }
        }
    }
}
