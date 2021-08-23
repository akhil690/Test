node {
  
  stage('SCM Checkout'){
    steps {
      echo"make checkout"
    git credentialsid: 'akhilhub', url: https://github.com/akhil690/Test.git

     }
  
  stage('Build project'){
    step {
    echo"Build my project successfully"
     }
     post {
        always {
           archiveartifacts: archiveArtifacts artifacts: 'Jenkinsfile', followSymlinks: false
        }
  }
