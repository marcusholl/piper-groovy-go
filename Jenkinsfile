
@Library('piper-lib-os') _

stage('Hello World') {
  echo "Hello World"
}

stage('deploy') {
  cloudFoundryDeploy script: this
}
 
