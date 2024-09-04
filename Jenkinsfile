//I am Stating Jenkis Today

pipeline {
    agent any
    stages{
        stage("checkout"){
            steps{
                echo "Here we clone the source code from repo....."
            }
        }
        stage("build"){
            steps{
                echo "We build the source code....."
            }
        }
        stage("test"){
            steps{
                echo "Conducting SonarQube Code Analysis....."
            }
        }
        stage("Deploy"){
            steps{
                echo "Here we Deploy the code....."
            }
        }
    }
}
