pipeline {
    agent any
    stages {
        stage ("Initialize") {
            steps {
                println ("Initializing System ...")
            }
        }
        stage ("Checkout") {
            steps {
                git branch: 'main', credentialsId: 'RahulGitConfig', url: 'https://github.com/rahche/github-test.git'
            }
        }
        stage ("Build") {
            steps {
                echo 'Greetings from build stage'
            }
        }
        stage ("Deploy") {
            steps {
                echo 'Greetings from deploy stage'
            }
        }
    }
} 
