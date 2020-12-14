pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh """
                 #!/bin/bash
                 echo "test"
                 echo "${env.GIT_BRANCH}"
                 echo "${env.GIT_COMMIT}"
                 """
            }
        }
    }
}
