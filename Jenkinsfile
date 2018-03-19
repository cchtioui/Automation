pipeline {
  agent {
    node {
      label 'SLAVE-W10-NEOLIANS'
    }
    
  }
  stages {
    stage('error') {
      steps {
        build(job: 'CreativeIT-CT', quietPeriod: 12)
      }
    }
  }
}