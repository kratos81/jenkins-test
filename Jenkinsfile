pipeline {
    // this is a modified branch
    /* I am adding this as a comment I want to test the rebase 
    make sure you pull these changes 
    */
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
