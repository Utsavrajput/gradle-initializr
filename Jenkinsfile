pipeline {
  agent any 
  stages {
    stage('Gradle'){
      steps {
        echo 'executing Gradle......'
        wihtGradle() {
          sh './gradlew -v'
        }
      }
    }
  }
}
