pipeline {
  agent {
          label 'master' 
  }
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
