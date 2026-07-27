pipeline {
    agent any

    tools{
        nodejs 'node24'
    }

    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm install --prefix src'
            }
        }

        stage('Run Application') {
            steps {
                sh 'npm start'
            }
        }
    }
}
