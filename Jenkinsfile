node('built-in') 
{
    stage('ContinuousDownload_Loans_branch') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('ContinuousBuild_Loans_branch') 
	{
    sh label: '', script: 'mvn package'
	}
}
