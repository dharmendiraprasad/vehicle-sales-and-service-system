pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo '--- Checking out source code ---'
                git branch: 'main',
                    url: 'https://github.com/dharmendiraprasad/vehicle-sales-and-service-system.git'
            }
        }

        stage('Verify Files') {
            steps {
                echo '--- Verifying project files ---'
                bat 'dir'
                bat 'if exist index.html (echo [OK] index.html found) else (echo [ERROR] index.html missing && exit /b 1)'
                bat 'if exist README.md (echo [OK] README.md found) else (echo [WARN] README.md missing)'
            }
        }

        stage('Archive Artifacts') {
            steps {
                echo '--- Archiving artifacts ---'
                archiveArtifacts artifacts: 'index.html, README.md', fingerprint: true
            }
        }
    }

    post {
        success {
            echo '============================================'
            echo ' BUILD SUCCESS - AutoPro VSSS is ready!'
            echo '============================================'
        }
        failure {
            echo '============================================'
            echo ' BUILD FAILED - Check console output above.'
            echo '============================================'
        }
    }
}
