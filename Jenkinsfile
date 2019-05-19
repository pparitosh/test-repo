pipeline {
    agent any
    triggers {
        pollSCM '* * * * *'
    }
    stages {
        stage('Run Script') {
            steps {
                // One or more steps need to be included within the steps block.
                sh label: '', script: './first.sh'
            }
        }
    }
}
