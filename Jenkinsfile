node('master') 
{
    stage('Continuous Download') 
	{
    git 'git clone https://github.com/TimeMachine00/multibranchJenkin.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
