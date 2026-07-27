pipeline {
    agent any

    tools{
        NodeJS 'node24'
    }

    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Run Application') {
            steps {
                sh 'npm start'
            }
        }
    }
}
