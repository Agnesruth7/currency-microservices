pipeline{
    agent{
        label 'java-slave'
    }
    stages{
        stage('Build'){
         steps{
             echo "Build the stage from feature Branch"
         }
        }
        stage('Scans'){
            steps{
                echo "Scan stage from feature Branch"
            }
        }
            stage('Docker'){
            steps{
                echo "Docker stage from feature Branch"
            }
        }
        stage('Production'){
            steps{
                echo "Production stage from feature Branch"
            }

            }
    }
}
