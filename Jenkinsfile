node('built-in') 
{
    stage('ContinuousDownload_Loans') 
	{
    git 'https://github.com/AbdulMuq1990/MultibranchRemoteRepo.git'
	}
    stage('ContinuousBuild_Loan') 
	{
    sh label: '', script: 'mvn package'
	}

}
