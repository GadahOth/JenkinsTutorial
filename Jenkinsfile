pipeline {
  agent any
  stages {
    stage('Norah') {
      parallel {
        stage('Norah') {
          steps {
            echo 'Be happy'
          }
        }

        stage('Hello') {
          steps {
            echo 'Hi'
          }
        }

        stage('ArchiveStage') {
          steps {
            archiveArtifacts(artifacts: 'target/*.jar', fingerprint: true)
          }
        }

      }
    }

  }
}