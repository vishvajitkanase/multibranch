pipeline {
    agent any
 
    stages {
        stage('Clone Git Repo') {
            steps {
                git branch: 'main', url: 'https://github.com/vishvajitkanase/jenkins-demo.git'
            }
        }

      stage('shell'){
        steps{
            sh ' pwd '
        }
      }
  }
}
