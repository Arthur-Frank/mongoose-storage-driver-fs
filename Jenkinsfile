pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                echo 'building'
                //withMaven(maven : 'maven_3_5_0') {
                    // sh 'mvn clean compile'
                //}
            }
        }

        stage ('Testing Stage') {

            steps {
                echo 'testing'
                //withMaven(maven : 'maven_3_5_0') {
                   // sh 'mvn test'
            }
        }


        stage ('Deployment Stage') {
            steps {
                echo 'deploying'
                //withMaven(maven : 'maven_3_5_0') {
                    // sh 'mvn deploy'
             //}
            }
        }
    }
}
