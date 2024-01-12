@Library('shared-jenkins-lib') _

def config = [name: 'Newman', dayOfWeek: 'Friday']

pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                helloWorld(config)
            }
        }
    }
}
