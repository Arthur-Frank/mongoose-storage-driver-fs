pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                withMaven(maven : 'maven_3_5_0') {
                    // sh 'mvn clean compile'
                    echo 'building'
                }
            }
        }

        stage ('Testing Stage') {

            steps {
                withMaven(maven : 'maven_3_5_0') {
                   // sh 'mvn test'
                    echo 'building'
                }
            }
        }


        stage ('Deployment Stage') {
            steps {
                withMaven(maven : 'maven_3_5_0') {
                    // sh 'mvn deploy'
                    echo 'building'
                }
            }
        }
    }
}
