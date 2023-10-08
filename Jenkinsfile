pipeline {
    agent any
    
    triggers {
        pollSCM('* * * * *') 
    }
    
    stages {
        stage('Hello') {
            steps {
                bat 'python3 new.py'
            }
        }
    }
}
