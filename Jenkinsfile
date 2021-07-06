node('master') 
{
    stage('Continuous Download') 
	{
    git 'git clone https://github.com/TimeMachine00/jenkinjob.giot'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
