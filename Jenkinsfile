node {

  stage('code checkout') {
    checkout scm
  }

  stage('list files') {
    ansiColor('xterm'){
      sh 'ls -l'
    }
  }

  stage('gradle tasks') {
    sh './gradlew tasks'
  }

  stage('sayHello') {
    sh './gradlew sayHello'
  }

}
