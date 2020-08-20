def workspace;
def name;
node 
{
 stage('checkout')
 {
    checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '7af88951-0b76-4397-8aab-3e026d6ec628', url: 'https://github.com/gshailendra1009/Web-Repo.git']]]) 
    workspace=pwd()
    echo workspace
 }
 stage('Static Code Analysis')
 {
    echo "Static Code analysis"
    name="Shailendra Gupta"
    echo "Hello $(name)"
 }
 stage('Build')
 {
    echo "Build the Application"
 }
 stage('Unit Testing')
 {
    echo "Perform Test cases" 
 }
 stage('Deployment')
 {
    echo "Deploy into Application Server" 
 }
 
}
