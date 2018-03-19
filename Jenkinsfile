pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        build(job: 'CreativeIT-CT', quietPeriod: 12)
      }
    }
  }
}