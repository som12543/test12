pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        sh '''mkdir test
minikube start
kubectl get nodes'''
      }
    }

  }
}