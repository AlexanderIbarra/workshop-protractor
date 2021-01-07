pipeline {
  agent any

  tools {nodejs "node"}

  stages {

    stage('Protactor-Workshop') {
      steps {
        git 'https://github.com/AlexanderIbarra/workshop-protractor'
         sh 'npm install'
         sh 'node test'
      }
    }
  }
}
