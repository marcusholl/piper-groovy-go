
@Library('piper-lib-os@v1.197.0') _

stage('Hello World') {
  echo "Hello World"
}

stage('deploy') {
  node() {
    cloudFoundryDeploy script: this
  }
}
 
