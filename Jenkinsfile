pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World is" ${env.SFDX_AUTH_STORE}'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
