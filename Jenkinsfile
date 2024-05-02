pipeline{

    agent any

    stages{'Git Checkout'}{
        steps{
            script{
                git branch: 'main', url: 'https://github.com/KavyaUST198606/java_app.git'
            }
        }
    }
}