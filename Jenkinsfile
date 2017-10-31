
pipeline {
    node {
        currentBuild.displayName = "displayNameJenkinsFile"
        currentBuild.description = "discriptionJenkinsFile"
    }
    agent any
    triggers {
        cron('*/1 * * * *')
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
