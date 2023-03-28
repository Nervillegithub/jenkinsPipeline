pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
         stage('build') {
            steps {
                echo 'building'
            }
        }
         stage('test') {
            steps {
                echo 'testing'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploy your application'
            }
        }
        stage('Release') {
            steps {
                echo 'Release to ecr'
            }
        }
    }
}
