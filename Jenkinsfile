pipeline {
    agent none
     stages{
        stage("build"){
            steps{
                echo "stage build"
            }
        }
        stage("Test"){
            steps {
                echo "stage test"
            }
        }
        stage("Run sh script"){
            steps{
                sh chmod +x project1.sh
                sh ./project1.sh
            }
        }
     }
}