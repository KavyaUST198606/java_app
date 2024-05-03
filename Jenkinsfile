@Library('SharedLibrary') _

pipeline{

    agent any

    stages{

        stage('Git Checkout'){
            
            steps{
            gitCheckout{
                branch: "main"
                url: "https://github.com/KavyaUST198606/java_app.git"
                    }

                }
            }
        }
    }