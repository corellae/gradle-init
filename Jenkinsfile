node {

  stage('code checkout') {
    checkout scm
  }

  stage('list files') {
    sh 'ls -l'
  }

  stage('gradle tasks') {
    sh './gradlew tasks'
  }

  stage('sayHello') {
    sh './gradlew sayHello'
  }

}
