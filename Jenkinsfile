pipeline {
    agent any
    
    triggers {
        pollSCM('* * * * *') 
    }
    
    stages {
        stage('Hello') {
            steps {
                sh 'python new.py'
            }
        }
    }
}
