pipeline {
  /*
   * TODO: Implement pipeline stages/steps
   *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
   */
  agent any
    stages {
      stage('Test') {
        steps {
          echo 'Running tests'
          sh './gradlew test'
        }
      }
      stage('Build') {
        steps {
          echo 'Assembling the project'
          sh './gradlew assemble'
        }
      }
    }
  
}
