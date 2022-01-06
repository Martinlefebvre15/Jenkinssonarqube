pipeline {
  agent any
  stages {
    stage('Int') {
      steps {
        sh '''mvn clean verify sonar:sonar \\
  -Dsonar.projectKey=Projet1 \\
  -Dsonar.host.url=http://localhost \\
  -Dsonar.login=fc44dddd9b4aa2024d2114c7686e494731b6430a'''
      }
    }

  }
}