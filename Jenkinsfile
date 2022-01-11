pipeline {
	//agent any
	agent { docker { image 'node:17' } }
	stages {
		stage('Build') {
			steps {
				echo "Node version is "
				sh 'node --version'
				echo "My Build success"
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

