pipeline{
    agent any
    parameters{
        choice(name:'Environment', choices: ['dev', 'qa', 'prod'])
    }
    stages{
        stage("git checkout"){
            steps{
                echo "this is git checkout"
            }
        }
        stage("build"){
            steps{
                echo "this is build on ${params.Environment}"
            }
        }
        stage("scanner"){
            steps{
                echo "this is code scanning stage"
            }
        }
    }
}