pipeline{
    agent{
        label "slave"
    }
    stages{
        stage("git checkout"){
            steps{
                echo "this is git checkout"
            }
        }
        stage("build"){
            steps{
                echo "this is build stage"
            }
        }
        stage("scanner"){
            steps{
                echo "this is code scanning stage"
            }
        }
    }
}