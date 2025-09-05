pipeline {
    agent any

    stages {
        stage('Stage 1: Checkout') {
            steps {
                echo "✅ Checkout stage running..."
            }
        }

        stage('Stage 2: Build') {
            steps {
                echo "✅ Build stage running..."
                sleep 5   // wait 5 sec so you can see it in Stage View
            }
        }

        stage('Stage 3: Test') {
            steps {
                echo "✅ Test stage running..."
                sleep 3
            }
        }

        stage('Stage 4: Deploy') {
            steps {
                echo "✅ Deploy stage running..."
            }
        }
    }

    post {
        success {
            echo "🎉 Pipeline finished successfully!"
        }
        failure {
            echo "❌ Pipeline failed!"
        }
    }
}
