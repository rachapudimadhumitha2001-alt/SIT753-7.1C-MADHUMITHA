pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Build code using Maven - Automatic SCM Polling Demonstration'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Run unit and integration tests using JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analyse code quality using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Perform security scanning using OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy application to staging using AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Run integration tests on staging using Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy application to production using AWS EC2'
            }
        }
    }
}
