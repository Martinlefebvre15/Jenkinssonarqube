pipeline {
  agent any
  stages {
    stage('Sonar') {
      steps {
        sh '''mvn clean verify sonar:sonar \\
  -Dsonar.projectKey=Projet1 \\
  -Dsonar.host.url=http://sonarqube:9000/ \\
  -Dsonar.login=fc44dddd9b4aa2024d2114c7686e494731b6430a'''
      }
    }

  }
}