node('built-in') 
{
    stage('ContinuousDownload_Master_branch') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('ContinuousBuild_Master_Branch') 
	{
    sh label: '', script: 'mvn package'
	}
}
