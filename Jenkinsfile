node('built-in') 
{
    stage('Continuous_Download_Master') 
	{
    git 'https://github.com/AbdulMuq1990/MultibranchRemoteRepo.git'
	}
    stage('ContinuousBuild_Master') 
	{
    sh label: '', script: 'mvn package'
	}

}
