@Library ('Pinkesh-shared-library')_
pipeline {
    agent any

    stages{

        stage('Test Shared Library'){
            steps{
                script{
                    Shared()            // shared library groovy file name in vars
                }
            }
        }
    }
}