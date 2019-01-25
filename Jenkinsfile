def workspace;
node
{
    stage ('Checkout')
    {
       checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '1f580791-cafe-4ea2-b7ef-e89037869cae', url: 'https://github.com/Deivid0797/Project1.git']]])
        workspace = pwd()
    }
    
    stage ('Static Code Analysis')
    {
        echo "Static Code Analysis"
    }
    stage ('Build')
    {
        echo "Buil the code"
    }
    stage ('Unit Testing')
    {
        echo "Unit Testing"
    }
    stage ('Delivery')
    {
        echo "Delivery the code"
    }
}
