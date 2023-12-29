pipeline {
    agent any
    stages {
        stage('Stage1') {
            when {
                branch 'production'
            }

            steps {
                echo 'Deploying'
            }
        }

        stage('Stage2'){
            steps {
                echo 'Deploying'
            }
        }
    }
}