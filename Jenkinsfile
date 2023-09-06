/* Requires the Docker Pipeline plugin */
node {
    stage('Build') {
        docker.image('python:3.11.5-alpine3.18').inside {
            sh 'python --version'
        }
    }
}
