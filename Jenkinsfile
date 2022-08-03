node('built-in') 
{
    stage('ContinuousDownload_Master') 
	{
    git 'https://github.com/AbdulMuq1990/MultibranchRemoteRepo.git'
	}
    stage('ContinuousBuild_Master') 
	{
    sh label: '', script: 'mvn package'
	}

}
