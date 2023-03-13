pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
  agent any
  stages {
    stage('Build'){
      steps {
        bat 'gradlew test'
      }
    }
  }
}
