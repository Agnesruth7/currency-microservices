pipeline{
    agent{
        label 'java-slave'
    }
    environment{
        name = "agnes"
        course = "Devops Engineer"
    }
    stages{
        stage ('first stage'){
            environment{
                cloud = "GCP"
            }
            steps{
                echo "welcome to devops ${name}"
            echo "you enrolled to ${course}"
            echo "you are certified in ${cloud}cloud"
            }
        }
    }
}
