node('built-in')
{
    stage('Continuous Download loans..') 
	{
    git 'https://github.com/PAG2k/CICDdemo.git'
	}
    stage('Continuous Build loans..') 
	{
    sh label: '', script: 'mvn package'
	}
}
