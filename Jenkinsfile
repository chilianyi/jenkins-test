pipeline {
  agent any
  stages {
    stage('stage-84kwt') {
      steps {
        echo 'ddd'
      }
    }

  }
  parameters {
    choice(name: 'Environments1', choices: ['dev', 'test', 'pre', 'pre2', 'prod'], description: 'desc')
    choice(name: 'Environments2', choices: ['dev', 'test', 'pre', 'pre2', 'prod'], description: 'desc')
    choice(name: 'ServicesDeploy1', choices: ['case-gateway', 'case-auth', 'case-admin', 'case-user', 'case-report', 'case-search', 'case-applet', 'all'], description: 'service')
  }
}
