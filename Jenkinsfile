pipeline{
    agent any // where to execute node1, linux node, windows node and etc
    stages{
        stage("build"){
            steps {
                echo "building stage "
                script{
                    def test= 2+3 > 3 ? 'cool': 'notcool'
                    echo "testing $test for webhooks testing"
                    echo " testing code for git-webhook"
                }
                }
        }
        stage("test"){
            steps {
                echo "testing stage "
                }
        }
        stage("deploy"){
            steps {
                echo "deoloying stage "
                }
        }
    }
}

