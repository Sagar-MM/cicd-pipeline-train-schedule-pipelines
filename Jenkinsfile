pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
      echo 'Build automation running'
      sh './gradlew build --no-deamon'
      archievArtifacts artifacts: 'dist/train-schedule.zip'
      }
    }  

  }

}
