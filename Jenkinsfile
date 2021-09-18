node('master') 
{
    stage('Continuous Download_orders') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_orders') 
	{
    sh label: '', script: 'mvn package'
	}
 }
