pipeline{
	agent any 
	stages{
		stage('0-action0'){
			steps{
				checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'jenkins-access', url: 'https://github.com/ArmandCantiller87/Techop-team8project.git']])
			}
		}
		stage('armand'){
			steps{
				 echo "member1: armand"
			}
		}
		stage('kenu'){
			steps{
				echo "member2: kenu"
			}
		}
		stage('thomas'){
			steps{
				echo "member3: thomas"
			}
		}
        stage('ben'){
            steps{
                echo "member4: ben"
            }
        }
        stage('erica'){
            steps{
                echo "member5: erica"
            }
        }
        stage('add-readmefile'){
            steps{
                sh " bash -x cp README.md /etc/tmp"
            }
        }
    
	}
}
