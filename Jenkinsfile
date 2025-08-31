pipeline {
  agent any

  triggers {
    // Runs every 15 minutes
    cron('H/2 * * * *')
  }

  stages {
    stage('Build') {
      steps {
        echo "Running build at ${new Date()}"
      }
    }
  }
}
