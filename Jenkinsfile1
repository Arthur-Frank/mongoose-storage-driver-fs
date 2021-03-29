pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                echo 'building'
            }
        }

        stage ('Testing Stage') {

            steps {
                echo 'testing'
            }
        }


        stage ('Deployment Stage') {
            steps {
                echo 'deploying'
            }
        }
    }
    post {
        always {
            archiveArtifacts artifacts: '**/*.jar', onlyIfSuccessful: true
        }
    }
}
