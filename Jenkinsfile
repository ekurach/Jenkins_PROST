pipeline {
		agent {
		dockerfile true
		}

		stages{
			stage('Build'){
				steps
				{
				 cmakeBuild buildType: 'Release', cleanBuild: true, installation: 'C:\Users\emili\source\repos\Jenkins_PROST', steps: [[withCmake: true]]
				}
			}
			
		}

}