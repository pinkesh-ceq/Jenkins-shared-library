@Library('Pinkesh-shared-library')_
pipeline {
    agent any

    stages{

        stage('Test Shared Library'){
            steps{
                script{
                    shared()            // shared library groovy file name in vars
                    shared.printName('Pinkesh')
                }
            }
        }
    }
}
