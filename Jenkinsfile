pipeline{
    agent any

    stages{

        stage("bulid"){
            steps{
                sh "./mvnw install"

            }
        }
        stage("run tests"){
            steps{
                sh "./mvnw test"
            }
        }
    }
 }

        