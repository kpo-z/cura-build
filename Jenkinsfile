pipeline {
    agent none

    stages {

        stage ('Run build') {
            agent { label 'jworker' }
                steps {
                     docker { image 'node:16.13.1-alpine' }
                 }
        }
    }
}
