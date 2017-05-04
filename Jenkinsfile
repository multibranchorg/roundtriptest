pipeline {
  agent any
  stages {
    stage('thing') {
      steps {
        sh 'echo 42'
        script {
          def initialize = load('jenkins/pipeline/initialize.groovy')
          initialize()
        }
        
      }
    }
  }
}
