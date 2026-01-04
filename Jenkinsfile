node('master') 
{
    stage('Continuous Download Main') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build Main') 
	{
    sh label: '', script: 'mvn package'
	}
}
