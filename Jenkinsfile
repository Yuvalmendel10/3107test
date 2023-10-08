pipeline {
    agent any
    
    triggers {
        pollSCM('* * * * *') 
    }
    
    stages {
        stage('Hello') {
            agent {
                label 'lin'
            }
            steps {
                sh 'python3 new.py'
            }
        }
    }
}
