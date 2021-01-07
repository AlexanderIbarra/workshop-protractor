pipeline {
  agent any

  tools {nodejs "NodeJS"}

  stages {

    stage('Protactor-Workshop') {
      steps {
        git 'https://github.com/AlexanderIbarra/workshop-protractor'
         sh 'npm install'
          sh 'npm run test:headless'
    }
  }
}
