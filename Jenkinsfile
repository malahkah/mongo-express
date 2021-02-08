pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        snykSecurity(organisation: 'malahkah', projectName: 'mango-express', severity: 'high', snykTokenId: '549c12cc-bb4b-429a-8b3a-331bc538ecac', monitorProjectOnBuild: true)
      }
    }

  }
}