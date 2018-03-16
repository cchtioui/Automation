pipeline {
  agent {
    node {
      label 'SLAVE-W10-NEOLIANS'
    }
    
  }
  stages {
    stage('') {
      steps {
        build(job: 'CreativeIT-CT', propagate: true, quietPeriod: 12, wait: true)
      }
    }
  }
}