node('master') 
{
    stage('Continuous Download_LoginMaster') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_LoginMaster') 
	{
    sh label: '', script: 'mvn package'
	}
}
