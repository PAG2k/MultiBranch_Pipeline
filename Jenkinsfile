node('master') 
{
    stage('Continuous Download main') 
	{
    git 'https://github.com/PAG2k/CICDdemo.git'
	}
    stage('Continuous Build main') 
	{
    sh label: '', script: 'mvn package'
	}
}
