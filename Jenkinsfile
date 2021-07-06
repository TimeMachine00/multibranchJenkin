node('master') 
{
    stage('Continuous Download') 
	{
          git 'https://github.com/TimeMachine00/multibranchJenkin.git'
	}
    stage('Continuous Build') 
	{
          sh 'mvn package'
	}
    
}
