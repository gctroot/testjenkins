pipeline {
  agent any
  stages {
    stage('pull code') {
      steps {
        sh '''pipeline {
  agent any

  stages {
    stage(\'Clone\') {
      steps {
        git \'https://github.com/gctroot/testjenkins.git\'
      }
    }
  }
}

'''
        }
      }

    }
  }