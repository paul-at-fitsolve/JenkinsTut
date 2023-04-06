/* Requires the Docker Pipeline plugin */
node {
    stage('Build') {
        docker.image('php:8.1.11-alpine').inside {
            sh 'php --version'
        }
    }
}