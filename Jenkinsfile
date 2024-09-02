pipeline {
    agent any

    stages {
        stage('Development') {
            steps {
                echo 'Development'
                bat '''git clone https://github.com/durva11chavan/yt_bookmark.git'''
            }
        }
        stage('QA') {
            steps {
                echo 'QA'
            }
        }
        stage('UAT') {
            steps {
                echo 'UAT'
            }
        }
        stage('PreProd') {
            steps {
                echo 'PreProd'
            }
        }
        stage('Prod') {
            steps {
                echo 'Prod'
            }
        }
    }
}
