pipeline {
    agent any
    
    triggers { 
        cron('H/1 * * * *')     
        pollSCM('H/2 * * * *')
    }

    stages {
        stage('Build') {
            steps {
                echo 'Pipeline started by a GitHub push!'
                bat 'dir /B'
            }
        }
    }
}
