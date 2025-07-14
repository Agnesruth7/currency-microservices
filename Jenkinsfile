pipeline{
    agent{
        label 'java-slave'
    }
    stages{
        stage('Build'){
         steps{
             echo "Build the stage from main Branch"
         }
        }
        stage('Scans'){
            steps{
                echo "Scan stage from main Branch"
            }
        }
            stage('Docker'){
            steps{
                echo "Docker stage from main Branch"
            }
        }
        stage('Production'){
            steps{
                echo "Production stage from main Branch"
            }

            }
    }
}
