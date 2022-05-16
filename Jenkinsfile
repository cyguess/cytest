pipeline {
	agent{ 
          node{
         label 'maven'
    }
   }
   stages{
     stage('Example Build'){
       steps{
      sh 'docker images' 
    }
   }
  }
}
