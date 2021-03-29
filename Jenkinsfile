node('master') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/ramreddyk1236/multibranching.git'
	}
    stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
