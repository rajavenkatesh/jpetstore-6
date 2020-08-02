pipeline {
    agent {
        image 'maven'
    }
    triggers {
        githubPush()
    }
    stages {
        stage("Build the code") {
            steps {
                sh 'mvn clean install'
            }
        }
   }
   }
