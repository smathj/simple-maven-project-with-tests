node('master') {
  checkout scm
  stage('Build') {   
    withMaven(maven: 'M3') {
      mvn --version
  }
  

}
