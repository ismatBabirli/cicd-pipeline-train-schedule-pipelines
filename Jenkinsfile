pipeline {
  agent any
  stages {
    stage('Build'){
      steps {
        echo 'Runing build automation'
        sh './gradelw build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
