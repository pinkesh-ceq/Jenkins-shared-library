@Library('Pinkesh-shared-library')_
pipeline {
    agent any

    stages{

        stage('Test Shared Library'){
            steps{
                script{
                    shared()            // shared library groovy file name in vars
                    welcome.printName("Pinkesh")
                    welcome.welcome("Hello from jenkins")
                }
            }
        }
    }
}
