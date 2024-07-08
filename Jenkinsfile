pipeline {
  agent {
    node {
      label 'node'
    }

  }
  stages {
    stage('production') {
      steps {
        git(url: 'https://github.com/anshumangautam2050/node-pipeline.git', branch: 'main')
      }
    }

  }
}