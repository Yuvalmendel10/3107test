pipeline {
    agent any
    
     triggers {
        pollSCM('* * * * *')
    }

    stages {
        stage('first stage') {
            steps {
                echo 'here is your code'
            }
        }
    }
}
