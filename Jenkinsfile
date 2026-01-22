pipeline {
    agent any

    environment {
        NOM = 'datascientest'
    }

    stages {
        stage('Test environment') {
            steps {
                sh 'echo $NOM'
            }
        }
    }
}
