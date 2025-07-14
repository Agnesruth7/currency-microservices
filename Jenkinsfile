pipeline{
    agent{
        label 'java-slave'
    }
    stages{
        stage('Build'){
         steps{
             echo "Build the application"
         }
        }
        stage('Scans'){
            steps{
                echo "performing sonar scans"
            }
        }
            stage('Dockerbuild'){
            steps{
                echo "implementing docker build"
            }
        }
        stage('devenv'){
            steps{
                echo "developing to devenv"
            }

            }
         stage('stageenv'){
            steps{
                echo "developing to stageenv"
            }
         }
         stage('prodenv'){
            steps{
                echo "developing to prodenv"
            }
         }
        
    }
}
