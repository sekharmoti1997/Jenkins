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
        stage("Artifact Deploy"){
            steps{
                echo "Here we Deploy the code....."
            }
        stage("Docker Container and Image Push"){
            steps{
                echo "Here we Create a container, Build an Image and Push it into the Registry......"
            }
        }
    }
}
