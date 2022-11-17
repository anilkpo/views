pipeline{
   agent any

   stages{
	stage('checkout'){
     steps{
       checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: '3c72b54d-2b80-429d-8b91-36c26b802990', url: 'https://github.com/anilkpo/views.git']]])
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
