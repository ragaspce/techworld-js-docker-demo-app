pipeline {
  agent any
  stages {
    stage("prebuild") {
      steps{
        echo " pre building "
      }
    }
    stage("build") {
      steps{
        echo "building"
        sh "arch"
        sh "cat /etc/os-release"
      }
    }
    stage("test & deploy") {
      steps{
        echo "test and deploy"
      }
    }
  }
}
