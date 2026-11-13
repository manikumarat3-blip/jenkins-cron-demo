pipeline {
    agent any

    triggers {
        cron('* * * * *')
    }

    stages {

        stage('Cron Test') {
            steps {
                echo "================================="
                echo "Cron triggered this Jenkins build"
                echo "Build Number: ${env.BUILD_NUMBER}"
                echo "Build Time: ${new Date()}"
                echo "================================="
            }
        }

    }
}
