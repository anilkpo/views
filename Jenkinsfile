pipeline{
   agent any

   stages{
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
       eco "artifacts upload is succesful"
    }
    }
	   
   }

	}
