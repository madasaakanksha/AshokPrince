pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploy'
            }
        }
        stage('test') {
            steps {
                echo 'test'
            }
        }
    }
             post {
                 always {
                    
                        emailext body: 'summary', replyTo: 'cashokkumarhpt1997@gmail.com', subject: 'summary', to: 'cashokkumarhpt1997@gmail.com' //post
                        }
                  }
    
}
