pipeline {
		agent any

		stages{
			stage('Build'){
				steps{
				 cmakeBuild buildType: 'Release', cleanBuild: true, installation: 'InSearchPath', steps: [[withCmake: true]
				}
			}
			
		}

}