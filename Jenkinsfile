// pipeline {
//     agent any
    
//     triggers { 
//         cron('H/1 * * * *')     
//         pollSCM('H/2 * * * *')
//     }

//     stages {
//         stage('Build') {
//             steps {
//                 echo 'Pipeline started by a GitHub push!'
//                 bat 'dir /B'
//             }
//         }
//     }
// }

pipeline {
    agent any
    stages {
        stage('Open HTML') {
            steps {
                echo 'Pipeline started for HTML!'
                bat 'start index.html'  // Windows
                // OR
                // sh 'xdg-open index.html'  // Linux
            }
        }
    }
}
