pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo '🔧 Building the application...'
                sh 'echo Build step - usually install dependencies here'
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Running tests in pro...'
                sh 'echo Test step - usually run pytest or other tests here'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying to staging...'
                sh 'echo Deployment step - deploy logic goes here'
            }
        }
    }
}
