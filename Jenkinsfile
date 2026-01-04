node('master') 
{
    stage('Continuous Download Main') 
	{
    git 'https://github.com/PAG2k/CICDdemo.git'
	}
    stage('Continuous Build Main') 
	{
    sh label: '', script: 'mvn package'
	}
}
