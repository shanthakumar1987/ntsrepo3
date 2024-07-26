pipeline {
  agent any
  stages {
    stage('SCM') {
      steps {
        git(url: 'https://github.com/shanthakumar1987/ntsrepo3', branch: 'main', credentialsId: '1efce57b-4df9-4715-9c62-dac27109bb4a', poll: true)
      }
    }

  }
}