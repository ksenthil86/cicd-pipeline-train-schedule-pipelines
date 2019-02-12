pipeline{
  agents any
  stages{
   stage('Build'){
    steps{
      sh './gradlew build'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip', fingerprint: true
      echo 'Deployed Successfully'
      }
   }
  }
 }
      
