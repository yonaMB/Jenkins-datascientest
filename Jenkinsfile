pipeline {
    agent any

    environment {
        DOCKER_ID = "dstdockerhub"
        DOCKER_IMAGE = "datascientestapi"
        DOCKER_TAG = "v.${BUILD_ID}.0"
    }

    stages {
        stage('Test variables Jenkins') {
            steps {
                echo "Docker ID = ${env.DOCKER_ID}"
                echo "Docker Image = ${env.DOCKER_IMAGE}"
                echo "Docker Tag = ${env.DOCKER_TAG}"
            }
        }
    }
}
