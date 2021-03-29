node('master') 
{
    stage('Continuous Download_master') 
	{
    git 'https://github.com/ramreddyk1236/multibranching.git'
	}
    stage('Continuous Build_master') 
	{
    sh label: '', script: 'mvn package'
	}
}
