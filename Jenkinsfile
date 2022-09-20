pipeline {
  agent {
          label 'master' 
  }
  stages {
    stage('Gradle'){
      steps {
        echo 'executing Gradle......'
        withGradle() {
          sh './gradlew -v'
          sh './gradlew init'
        }
      }
    }
  }
}
