pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        sleep 1
      }
    }
    stage('Browser Tests') {
      parallel {
        stage('Firefox') {
          steps {
            sleep 1
          }
        }
        stage('Chrome') {
          steps {
            sleep 1
          }
        }
        stage('Edge') {
          steps {
            sleep 1
          }
        }
        stage('Safari') {
          steps {
            sleep 1
          }
        }
      }
    }
    stage('Security ') {
      parallel {
        stage('Compliance ') {
          steps {
            sleep 1
          }
        }
        stage('Static Analysis') {
          steps {
            sleep 1
          }
        }
        stage('DAST') {
          steps {
            sleep 1
          }
        }
        stage('Dependency Vulnerability Scan') {
          steps {
            sleep 1
            sh '''asdswqww
asfdds'''
          }
        }
        stage('Artifact Signing') {
          steps {
            echo 'done'
          }
        }
      }
    }
    stage('Deploy') {
      steps {
        echo 'done'
      }
    }
  }
}