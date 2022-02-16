
@Library('piper-lib-os@19a05a9c709fcb9b6376054393730f23893ce2ee') _

stage('Hello World') {
  echo "Hello World"
}

stage('deploy') {
  node() {
    cloudFoundryDeploy script: this
  }
}
 
