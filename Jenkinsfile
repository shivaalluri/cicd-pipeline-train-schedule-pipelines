pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh './gradlewbuild --no-daemon'
        archiveArtifacts: 'dist/trainSchedule.zip'
        }
     }
  }
}
  
