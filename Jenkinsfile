pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building 5G Kubernetes Project'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Kubernetes Cluster'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Application'
            }
        }

        stage('Monitoring') {
            steps {
                echo 'Checking Grafana and Prometheus'
            }
        }
    }
}
