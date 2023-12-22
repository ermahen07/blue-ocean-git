pipeline {
  agent {
    node {
      label 'Slave1'
    }

  }
  stages {
    stage('build') {
      steps {
        echo 'this is build project'
      }
    }

    stage('test') {
      steps {
        sh '''ls
pwd 
git clone https://github.com/ermahen07/jenkins-demo.git
mkdir rin '''
      }
    }

    stage('deploy') {
      steps {
        sleep 10
      }
    }

    stage('prod') {
      steps {
        echo 'plz produce'
      }
    }

  }
  environment {
    mahen = 'kumar'
  }
}