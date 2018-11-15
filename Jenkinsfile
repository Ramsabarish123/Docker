pipeline{
	agent{ docker 'busybox' }
	stages{
		stage('step1'){
			steps{
				docker.inside{ "echo hi"}
			}
		}
	}
}

