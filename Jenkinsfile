pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/your-username/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
                // Example: sh 'mvn clean install'   (for Java project)
                // Example: sh 'python3 -m compileall .'   (for Python project)
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example: sh 'pytest tests/'  (for Python tests)
                // Example: sh 'npm test'      (for Node.js)
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Example: sh './deploy.sh'   (custom deployment script)
            }
        }
    }
}
