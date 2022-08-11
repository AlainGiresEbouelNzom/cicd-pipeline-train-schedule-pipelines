node {
  stage('gradle build'){
  sh './gradlew build --no-daemon'
    archiveArtifacts artifacts: 'dist/trainSchedule.zip'
  }
}
