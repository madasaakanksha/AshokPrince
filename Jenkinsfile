pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build'
            }
        }
        stage('test') {
            steps {
                echo 'test'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploy'
            }
        }
        post
        {
            always
            {
                emailext body: 'summary', replyTo: 'cashokkumarhpt1997@gmail.com', subject: 'summary', to: 'cashokkumarhpt1997@gmail.com'
            }
        }
    }
}
