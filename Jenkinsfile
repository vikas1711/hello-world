def workspace
node 
{
    stage('Checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/vikas1711/hello-world.git']]])
        workspace = pwd()
    }
    stage('Codereviw')
    {
        echo "static code"
    }
   
}
