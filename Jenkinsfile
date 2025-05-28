pipeline{
    agent any

    stages{

        stage("bulid"){
            steps{
                sh "./mvnw install"

            }
        }

        stage("Run unit tests") {
             steps {
                 sh "./mvnw test"
             }
         }

        
    }
 }

        