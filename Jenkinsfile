pipeline{
   agent any

   stages{
	stage('checkout'){
     steps{
       checkout([$class: 'GitSCM', branches: [[name: '*/develop']], extensions: [], userRemoteConfigs: [[credentialsId: '29c63980-2a46-4aa1-a58e-4fac76ef5e16', url: 'https://github.com/anilkpo/views.git']]])
    } 
    }
    stage('Build'){
     steps{
       echo "Build succesfful"
    }
    }
    stage('Test'){
     steps{
       echo "Test succesfful"
    }
    }
     stage('Scan'){
     steps{
       echo "security scan succesful"
    }
    }
 stage('upload artifacts'){
     steps{
       echo "artifacts are ploaded succesfully"
    }
    }
	
   }

	}
