pipeline {
    agent any
    stages {
        stage('Running shell scripts') {
            steps {
                sh '''
                myVar = "Big Chungus"
                echo myVar
                bash ./hello.sh
                '''
            }
        }
        
    }
}
