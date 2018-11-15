pipeline{
	agent any
	stages{
		stage('step1'){
			steps{
				docker.image('busybox').inside{sh 'echo hi'}
			}
		}
	}
}

