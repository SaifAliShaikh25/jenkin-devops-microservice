pipeline {
	agent any
	environment{
		mavenHome = tool 'myMaven'
		PATH = "$mavenHome/bin:$PATH"
	}
	stages {
		stage('Build') {
			steps {
				//sh 'docker version'
				//sh 'mvn --version'
				echo "My Build success"
				echo "Path is - $PATH"
				echo "Build number - $env.BUILD_NUMBER"
				echo "Build id - $env.BUILD_ID"
				echo "Job name - $env.JOB_NAME"
				echo "Build tag - $env.BUILD_TAG"
				echo "Build url - $env.BUILD_URL"
			}
		}
		stage('Test') {
			steps {
				echo "Test success"
			}
		}
	}
}
// node {
// 	stage('Build') {
// 		echo "Build"
// 	}
// 	stage('Test') {
// 		echo "Test"
// 	}
// 	stage('Integration Test') {
// 		echo "Integration Testing"
// 	}

// 	stage('Integration Test') {
// 		echo "Integration Testing again"
// 	}
// }

//Declarative syntax
// pipeline {
// 	agent any
// 		stages {
// 		stage('Build') {
// 			steps {
// 				echo "My Build success"
// 			}
// 		}
// 	}
// }

